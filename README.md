# projetosPython
# nesse projeto aprendi a inserir variaveis em Python, e operadores aritmeticos.

# 1-peca para  usuario inserir 2 numero e imprima a soma, 
# a diferenca, a divisao dos mesmo em python

primeiro_numero = float(input('insira o prmeiro numero\n'))
segundo_numero = float(input('insira o segundo numero\n'))
print('resultado da soma e')
print (primeiro_numero + segundo_numero )
print('resultado da subtracao e')
print (primeiro_numero - segundo_numero)
print('resultado da diferenca e')
print (primeiro_numero != segundo_numero)
print('resultado da divisao  e')
print (primeiro_numero / segundo_numero)
print('resultado da multiplicacao e')
print (primeiro_numero * segundo_numero)

# 2. Solicite ao usuário que insira um número e determine se é positivo, 
# negativo ou zero.

numero = int(input("insira primeiro numero\n"))    

if numero > 0:
    print('numero positivo')
elif numero < 0:
    print('numero negativo')
else:
    print('numero 0')
