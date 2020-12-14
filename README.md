# NOTAS
Retorna se o aluno foi aprovado ou não.

n1 = float(input("Digite a primeira nota: "))
n2 = float(input("Digite a segunda nota: "))


if ((n1 + n2)/2) == 10:

  print("ALUNO APROVADO COM DISTINÇÃO")


elif ((n1 + n2)/2) >= 7:

  print("ALUNO APROVADO")

else:
  print("ALUNO REPROVADO")
