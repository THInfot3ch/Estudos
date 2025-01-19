# Estudos

Python

-Sintaxe Básica:

Variáveis e Tipos de Dados
Operadores
Estruturas de Controle (if, else, elif)
Loops (for, while)

-Funções:

Definição de Funções
Argumentos e Parâmetros
Retorno de Valores

-Estruturas de Dados:

Listas
Tuplas
Dicionários
Conjuntos

-Manipulação de Strings:

Métodos de String
Formatação de Strings

-Módulos e Pacotes:

Importação de Módulos
Criação de Módulos

-Tratamento de Exceções:

Try, Except, Finally

-Programação Orientada a Objetos:

Classes e Objetos
Herança
Polimorfismo

-Bibliotecas Comuns:

NumPy
Pandas
Matplotlib


------------------------------------------------------------------------------------
1. Introdução ao Python
O que é Python?

Linguagem de programação de alto nível, interpretada e de propósito geral.
Usada em desenvolvimento web, automação, análise de dados, inteligência artificial, etc.

------------------------------------------------------------------------------------
2. Sintaxe Básica
Variáveis e Tipos de Dados

nome = "João"  # String
idade = 25     # Inteiro
altura = 1.75  # Float

Operadores

soma = 5 + 3
subtracao = 10 - 2
multiplicacao = 4 * 2
divisao = 8 / 2
------------------------------------------------------------------------------------
3. Estruturas de Controle

Condicionais (if, else, elif)

if idade >= 18:
    print("Maior de idade")
else:
    print("Menor de idade")

    3.1 --------------
    
    Loops (for, while)

for i in range(5):
    print(i)

contador = 0
while contador < 5:
    print(contador)
    contador += 1
   
------------------------------------------------------------------------------------
4. Funções
Definição e Uso de Funções

def saudacao(nome):
    return f"Olá, {nome}!"

print(saudacao("Mundo"))
------------------------------------------------------------------------------------
5. Estruturas de Dados
Listas

frutas = ["maçã", "banana", "cereja"]
print(frutas[0])  # Acessa o primeiro elemento

*----- 
Tuplas

coordenadas = (10, 20)
print(coordenadas[0])  # Acessa o primeiro elemento

*----------
Dicionários

pessoa = {"nome": "João", "idade": 25}
print(pessoa["nome"])  # Acessa o valor associado à chave "nome"

*----------
Conjuntos

numeros = {1, 2, 3, 4, 5}
print(numeros)
------------------------------------------------------------------------------------
6. Manipulação de Strings
Métodos de String

texto = "Olá, Mundo!"
print(texto.upper())  # Converte para maiúsculas
print(texto.lower())  # Converte para minúsculas

*----------------
Formatação de Strings

nome = "João"
idade = 25
print(f"Meu nome é {nome} e eu tenho {idade} anos.")
------------------------------------------------------------------------------------
7. Módulos e Pacotes
Importação de Módulos

import math
print(math.sqrt(16))  # Calcula a raiz quadrada de 16

*--------------
Criação de Módulos

# Em um arquivo chamado meu_modulo.py
def saudacao(nome):
    return f"Olá, {nome}!"

# Em outro arquivo
import meu_modulo
print(meu_modulo.saudacao("Mundo"))

------------------------------------------------------------------------------------
8. Tratamento de Exceções
Try, Except, Finally

try:
    resultado = 10 / 0
except ZeroDivisionError:
    print("Erro: Divisão por zero!")
finally:
    print("Operação finalizada.")
------------------------------------------------------------------------------------
9. Programação Orientada a Objetos
Classes e Objetos

class Pessoa:
    def __init__(self, nome, idade):
        self.nome = nome
        self.idade = idade

    def saudacao(self):
        return f"Olá, meu nome é {self.nome} e eu tenho {self.idade} anos."

joao = Pessoa("João", 25)
print(joao.saudacao())

----Herança

class Estudante(Pessoa):
    def __init__(self, nome, idade, matricula):
        super().__init__(nome, idade)
        self.matricula = matricula

    def saudacao(self):
        return f"Olá, meu nome é {self.nome}, eu tenho {self.idade} anos e minha matrícula é {self.matricula}."

maria = Estudante("Maria", 22, "12345")
print(maria.saudacao())


------------------------------------------------------------------------------------
10. Bibliotecas Comuns
------NumPy

import numpy as np
array = np.array([1, 2, 3, 4])
print(array)

----Pandas

import pandas as pd
dados = {"Nome": ["João", "Maria"], "Idade": [25, 22]}
df = pd.DataFrame(dados)
print(df)

----Matplotlib

import matplotlib.pyplot as plt
plt.plot([1, 2, 3, 4], [1, 4, 9, 16])
plt.show()

-----------------------------------------------------


Conclusão
Projetos Práticos
Desenvolvimento Web com Django ou Flask
Análise de Dados com Pandas e Matplotlib
Automação de Tarefas com Scripts Python
Use este esboço para criar um PDF bem estruturado e didático. Boa sorte nos seus estudos de Python!
