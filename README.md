# Tabuada Simples em Python

<div align="center"> <p>Um script simples em Python que gera a tabuada de um número fornecido pelo usuário.</p> </div>

# Descrição
O programa solicita que o usuário digite um número inteiro e exibe sua tabuada de <strong>1 a 10</strong>, mostrando o resultado de cada multiplicação de forma clara e organizada.

# Codigo 

<details>
    <summary><strong>Clique para ver o código</strong></summary>
  
  ```python
  numero = int(input('Digite um numero para ver sua tabuada: '))
  for n in range(1, 11):
      print('{} x {} = {}'.format(numero, n, numero * n))
```
</details>

## 
# Como Funciona
    
<ol> <li><strong><code>input()</code></strong>: Solicita ao usuário um número (retorna uma string).</li> <li><strong><code>int()</code></strong>: Converte a entrada em um número inteiro e armazena em <code>numero</code>.</li> <li><strong><code>for n in range(1, 11)</code></strong>: Loop que itera de 1 a 10.</li> <li><strong><code>print()</code></strong>: Exibe a multiplicação no formato <em>"numero x n = resultado"</em>.</li> <li><strong><code>.format()</code></strong>: Formata a string com os valores de <code>numero</code>, <code>n</code> e o resultado.</li> </ol>

##

Exemplo de Uso

Se o usuário digitar <code>5</code>, a saída será:

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

<div align="center"> <strong>Resultado simples e direto!</strong> </div>

