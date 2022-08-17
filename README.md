
# 01) Tipo de Variaveis
#   a) Numéricas -
#     - Inteiro (Int)
#     - Ponto Flutuante ou Decimal (Float)
#   b) Caractere
#     - String (Str)
#   c) Lógicos
#     - Boleanas (Boal)

# 02) Aritiméticas
#     - Adição +
#     - Subtração -
#     - Multiplicação *
#     - Divisão /
#     - Divisão Inteira //
#     - Potência **
#     - Módulo (Resto) %
#     - Procedência de operação ()

# 02) Relacionais
# input('<texto(opcional)>')

# 03) Lógicas

<NomeCampo> = float(input('<Texto Opcional>')) # Convertndo o campo em tipo float 
# type()  Informa qual o tipo da variável



# --- Exercicio -----------------------------------------------------
# <Variável> = <Valor>
# <nome> = <Valor>
# Print()  Demostra o resultado

print('Excercicio 01) Tipo de Variaveis')
Idade = 21              # Int
Altura = 1.98           # Float
Nome = 'Ozzy Osborne'   # String

print('--- Dados do Cliente ---')
print(Nome)
print("Sua idade:", Idade)
print("Sua altura:", Altura)

print('Excercicio 02) Aritiméticas')
print('Divisão 5/3 =', 5 / 3)
print('Divisão Inteiro 5//3 =', 5//3)
print('Potência 5**2 =', 5**2)
print('Módulo 5%3 =', 5 % 3)
print('Procedência 5+3*2 =', (5 + 3) * 2)

NomeAluno = input('Digite o seu nome: ')        # comando 'input' solicita a digitação do campo
print('Seu nome é:', NomeAluno)

# Converter o resultado de texto (str) para inteiro (int)
IdadeAtual = input('Digite dua idade atual:')   # comando 'input' solicita a digitação do campo
IdadeAtual = int(IdadeAtual)
print(type(IdadeAtual))

AlturaAtual = float(input('Digite dua idade atual:'))   # comando 'input' solicita a digitação do campo
print(type(AlturaAtual))

