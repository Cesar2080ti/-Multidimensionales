def ordenar_fila(matriz, fila):
    fila_ordenada = sorted(matriz[fila])
    matriz[fila] = fila_ordenada
    return matriz

def imprimir_matriz(matriz):
    for fila in matriz:
        print(fila)

# Definir la matriz
matriz = [
    [3, 2, 9],
    [5, 1, 6],
    [8, 4, 7]
]

# Mostrar la matriz original
print("Matriz original:")
imprimir_matriz(matriz)

# Ordenar una fila específica (por ejemplo, la primera fila)
fila_a_ordenar = 0
matriz_con_fila_ordenada = ordenar_fila(matriz, fila_a_ordenar)

# Mostrar la matriz con la fila ordenada
print("\nMatriz con la fila ordenada:")
imprimir_matriz(matriz_con_fila_ordenada)
