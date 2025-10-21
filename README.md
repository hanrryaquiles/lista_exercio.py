# lista_exercio.py
Lista de exercícios 
numeros = [10, 20, 30, 40, 50]
print("Lista inicial:", numeros)

print("Primeiro número:", numeros[0])
print("Número do meio:", numeros[2])
print("Último número:", numeros[-1])

numeros[1] = 25
print("Lista atualizada:", numeros)

novo_num = int(input("Digite um número para adicionar à lista: "))
numeros.append(novo_num)
print("Lista atualizada:", numeros)

numeros.remove(30)
print("Lista após remover o 30:", numeros)
