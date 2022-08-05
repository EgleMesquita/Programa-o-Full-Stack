# Programa-o-Full-Stack
# Aula 03/08/2022 - Criação de um sistema de notas no sistema VISUALG

Algoritmo "semnome"


Var

Nome : Caracter
Ano: Inteiro
Turno : Caracter
Turma : Caracter
NotaA : Real
NotaB : Real
NotaC : Real
NotaD : Real
Media : Real
NotaMedia : Real

Inicio

Escreval("--------------------| DADOS DO ALUNO |--------------------")
Escreva("Nome: ")
       Leia(Nome)
Escreva("Ano: ")
       Leia(Ano)
Escreva("Turma: ")
       Leia(Turma)
Escreva("Média: ")
       Leia(Media)
Escreval("-------------------------| NOTAS |-------------------------")

Escreva("AV1: ")
       Leia(NotaA)
Escreva("AV2: ")
       Leia(NotaB)
Escreva("AV3: ")
       Leia(NotaC)
Escreva("AV4: ")
       Leia(NotaD)

NotaMedia := (NotaA + NotaB + NotaC + NotaD) / 4
Escreva("Média: ", NotaMedia, " ")

SE NotaMedia > Media ENTAO
   Escreval("Aprovado")
SENAO
   SE NotaMedia < Media ENTAO
      Escreval("Reprovado")
   SENAO
     Escreval("Recuperação")
   FIMSE
FIMSE
   
Escreval("-----------------------------------------------------------")

Fimalgoritmo
