# Excercicio

# Inserir dados
Lado = int(input('Digite o valor do Lado: '))
print('Lado:', Lado)

Base = int(input('Digite o valor do Base: '))
print('Base:', Base)

Altura = float(input('Digite o valor do Altura: '))
# print('Altura:', round(Altura, 3))
print(f'Altura: {Altura:,.2f}')

Raio = int(input('Digite o valor do Raio: '))
print('Raio:', Raio)

# Resultados
print('01) Faça um programa que receba o valor do lado de um quadrado, em seguida calcule a sua área e exiba a área na tela.')
print(f'R) Area = lado x lado = {Lado} x {Lado} =', Lado * Lado)

print('')
print('02) Faça um programa que receba o valor da base e da altura de um triângulo, em seguida calcule a sua área. Exiba a área da tela.')
print(f'R) Area = Base x altura / 2 = {Base} x {Altura} / 2 =', Base * Altura / 2)

print('')
print('03) Faça um programa que receba o valor do raio de um círculo em seguida calcule a sua área. Exiba a área na tela.')
print(f'R) Area = pi x raio ao quadrado = 3.14 x {Raio} =', 3.14 * (Raio ** 2))
