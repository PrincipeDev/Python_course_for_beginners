# Python_course_for_beginners

Claro! Aqui estão alguns exercícios de programação em Python, organizados por nível de dificuldade: fácil, médio e difícil.

### Nível Fácil

1. **Soma de Dois Números**
   - Escreva um programa que peça ao usuário para digitar dois números e exiba a soma deles.

2. **Par ou Ímpar**
   - Crie um programa que peça ao usuário para digitar um número e determine se ele é par ou ímpar.

3. **Contagem de Caracteres**
   - Faça um programa que peça uma string ao usuário e conte quantos caracteres essa string possui.

4. **Tabuada**
   - Escreva um programa que exiba a tabuada de um número fornecido pelo usuário (de 1 a 10).

5. **Conversão de Temperatura**
   - Crie um programa que converta uma temperatura de Celsius para Fahrenheit e vice-versa.

### Nível Médio

1. **Contagem de Vogais**
   - Escreva um programa que peça ao usuário para digitar uma string e conte quantas vogais (a, e, i, o, u) existem na string.

2. **Número Primo**
   - Faça um programa que determine se um número fornecido pelo usuário é primo.

3. **Ordenação de Lista**
   - Crie um programa que peça ao usuário para digitar uma lista de números e exiba a lista ordenada em ordem crescente.

4. **Fatorial**
   - Escreva um programa que calcule o fatorial de um número fornecido pelo usuário.

5. **Palíndromo**
   - Crie um programa que verifique se uma palavra fornecida pelo usuário é um palíndromo (ou seja, se lê da mesma forma de trás para frente).

### Nível Difícil

1. **Fibonacci**
   - Escreva um programa que exiba os primeiros n números da sequência de Fibonacci, onde n é fornecido pelo usuário.

2. **Calculadora**
   - Crie uma calculadora que execute as operações básicas (adição, subtração, multiplicação, divisão) com dois números fornecidos pelo usuário. O programa deve permitir a escolha da operação a ser realizada.

3. **Jogo da Forca**
   - Desenvolva um jogo da forca em que o usuário tenha que adivinhar uma palavra escolhida aleatoriamente pelo programa. O usuário deve ter um número limitado de tentativas.

4. **Cifra de César**
   - Implemente a Cifra de César, que é uma técnica de criptografia simples em que cada letra da mensagem é deslocada um número fixo de posições no alfabeto. O programa deve permitir que o usuário escolha a mensagem e o número de posições para o deslocamento.

5. **Ordenação Rápida (Quick Sort)**
   - Escreva um programa que implemente o algoritmo de ordenação rápida (Quick Sort) para ordenar uma lista de números fornecida pelo usuário.

### Exemplos de Implementações

#### Fácil

**1. Soma de Dois Números**
```python
num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))
soma = num1 + num2
print(f"A soma de {num1} e {num2} é {soma}")
```

#### Médio

**1. Contagem de Vogais**
```python
string = input("Digite uma string: ").lower()
vogais = "aeiou"
contagem = sum(1 for char in string if char in vogais)
print(f"A string possui {contagem} vogais")
```

#### Difícil

**1. Fibonacci**
```python
n = int(input("Quantos termos da sequência de Fibonacci você deseja? "))
fibonacci = [0, 1]
for i in range(2, n):
    fibonacci.append(fibonacci[-1] + fibonacci[-2])
print(fibonacci[:n])
```

Esses exercícios cobrem uma variedade de conceitos básicos e intermediários de programação em Python e podem ser ajustados conforme necessário para atender ao nível de habilidade e interesse dos alunos.