# exercicio007.py
#Desenvolva um programa que leia as duas notas de um aluno, calcule e mostre a sua média

n1 = int(input('nota 1: '))
n2 = int(input('nota 2: '))
r = (n1 + n2)/2

print('{:.1f} + {:.2f} = {:.2f}'.format(n1,n2,r))
