# Aula_6Python
# **Exercício 1:** Crie uma lista chamada `numeros` que contenha os números inteiros de 1 a 5 e imprima-a na tela.

lista = [1,2,3,4,5]
print(lista)




# **Exercício 2:** Acesse e imprima o terceiro elemento da lista `numeros`.
x = lista[2]
print(x)


# **Exercício 3:** Adicione o número 6 à lista `numeros` e imprima a lista atualizada.


lista.append(6)
print(lista)


# **Exercício 4:** Remova o número 3 da lista `numeros` e imprima a lista resultante.



del lista[2]
print(lista)


# **Exercício 5:** Crie uma lista chamada `frutas` contendo três nomes de frutas diferentes. Em seguida, concatene essa lista com a lista `numeros` e imprima o resultado.

frutas = ['maçã', 'melão', 'uva']
juntando  =  frutas + lista
print(juntando)



# **Exercício 6:** Use um loop `for` para percorrer e imprimir todos os elementos da lista `frutas`.

for i in frutas: 
     print(i)




# **Exercício 7:** Verifique se o número 25 está presente na lista `numeros` e imprima uma mensagem informando se ele está na lista ou não.

# numeros2 = [15,23,5,9,78,25]

# numero = 25
# if numero in numeros2:
#    print(f'existe o numero {numero}')
# else:
#    print(f'Não existe {numero}')
