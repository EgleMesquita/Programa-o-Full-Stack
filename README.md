# Programa-o-Full-Stack
Curso de Programação Full Stack na Acadêmico da Infinity School

Algoritmo "semnome"
// 1) Leia o valor do lado de um quadrado, calcule a sua área.
//    Exiba o resultado na tela. area = lado * lado(ou lado²)


// 2) Leia três notas, calcule a sua média e exiba na tela.


// 3) Leia a base e a altura de um triângulo. Em seguida calcule a sua área.
//    Exiba a área na tela. area = base * altura / 2

// 4) Leia a base e a altura de um retangulo e calcule a área.
//    Exiba a área na tela. Area = Base x Altura

// 5) Leia a base menor, base maior e altura de um trapézio.
//     Em seguida calcule a sua áreae a exiba na tela
//     Area = (Base maior + Base Menor) x Altura / 2

// 6) Leia o raio de um ciurculo e calcule a suia área. Em seguida exiba a área na tela
//     Area = pi x Raio ^ 2 (ou Raio x Raio)
Var

// 1
Area : Real
Lado : Real

// 2
Av1 : Real
Av2 : Real
Av3 : Real
Media : Real

// 3 e 4
Base : Real
Altura : Real

// 5
BaseMaior : Real
BaseMenor : Real

// 6
Raio : Real
ValorPI : Real


Inicio


Escreval("1) Leia o valor do lado de um quadrado, calcule a sua área.")
Escreval("-----------------------------------------------------------------")

Escreva("Lado: ")
Leia(Lado)

Escreval("Area: ", Lado, " x", Lado, " = ", Lado * Lado, "cm")

Escreval("")



Escreval("2) Leia três notas, calcule a sua média e exiba na tela")
Escreval("-----------------------------------------------------------------")

Escreva("AV1: ")
Leia(AV1)

Escreva("AV2: ")
Leia(AV2)

Escreva("AV3: ")
Leia(AV3)

Escreval("Media: (", AV1:1:1, " + ", AV2:1:1," + ", AV3:1:1,") / 3 = ", (AV1 + AV2 + AV3) / 3:2:1)

Escreval("")



Escreval("3) Leia a base e a altura de um triângulo. Em seguida calcule a sua área")
Escreval("-----------------------------------------------------------------")

Escreva("Base: ")
Leia(Base)

Escreva("Altura: ")
Leia(Altura)

Escreva("Area: (", Base:2:3, " x ", Altura:2:3, ") / 2 = " , (Base * Altura) / 2:2:3 )
Leia(Area)

Escreval("")



Escreval("4) Leia a base e a altura de um retangulo e calcule a área.")
Escreval("-----------------------------------------------------------------")

Escreva("Base: ")
Leia(Base)

Escreva("Altura: ")
Leia(Altura)

Escreva("Area: ", Base:2:3, " x ", Altura:2:3, " = " , (Base * Altura):2:3 )
Leia(Area)

Escreval("")



Escreval("5) Leia a base menor, base maior e altura de um trapézio.")
Escreval("-----------------------------------------------------------------")

Escreva("BaseMaior: ")
Leia(BaseMaior)

Escreva("BaseMenor: ")
Leia(BaseMenor)

Escreva("Altura: ")
Leia(Altura)

Escreva("Area: (", BaseMaior:2:3, " x ", BaseMenor:2:3, ") x ", Altura, " / 2 = " , ((BaseMaior + BaseMenor) * Altura ) / 2:2:3 )
Leia(Area)


Escreval("")



Escreval("6) Leia o raio de um ciurculo e calcule a suia área. Em seguida exiba a área na tela.")
Escreval("-----------------------------------------------------------------")

Escreva("Raio: ")
Leia(Raio)

ValorPI <- 3.1416

Escreva("Area: (", ValorPI:2:3, " x ", Raio:2:3, ") ^ 2 = " , (ValorPI * Raio) ^ 2)
Leia(Area)







Fimalgoritmo
