# Tabuada Simples em Python

<div align="center"> <p>Um script simples em Python que gera a tabuada de um número fornecido pelo usuário.</p> </div>

# Descrição
O programa solicita que o usuário digite um número inteiro e exibe sua tabuada de <strong>1 a 10</strong>, mostrando o resultado de cada multiplicação de forma clara e organizada.

numero = int(input('Digite um numero para ver sua tabuada: '))
for n in range(1, 11):
    print('{} x {} = {}'.format(numero, n, numero * n))

    Como Funciona
input(): Solicita que o usuário digite um número. A função input() retorna uma string.
int(): Converte a entrada do usuário (string) para um número inteiro e armazena na variável numero.
for n in range(1, 11): Cria um loop que itera de 1 a 10 (o range(1, 11) inclui 1 e exclui 11).
print(): Exibe a multiplicação no formato "numero x n = resultado", onde:
numero é o valor digitado pelo usuário.
n é o contador do loop (de 1 a 10).
numero * n é o resultado da multiplicação.
.format(): Formata a string para incluir os valores de numero, n e o resultado da multiplicação.

Exemplo de Uso
Se o usuário digitar 5, a saída será:

Digite um numero para ver sua tabuada: 5
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50


