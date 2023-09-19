# CNH

MAIOR_IDADE = 18
IDADE_MENOR = 17
idade = int(input("Informe sua idade: "))

if idade >= MAIOR_IDADE:
    print("Maior de idade, pode tirar a CNH.")
elif idade == IDADE_MENOR:
    print("somente aulas praticas")
else:
    print("Ainda não pode tirar a CNH.")
