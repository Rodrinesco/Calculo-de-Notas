# Calculo-de-Notas
#Programa para calcular notas de faculdade. (BETA). 
p1 = float(input('Digite a primeira nota: '))
p2 = float(input('Digite a segunda nota: '))
t1 = float(input('Digite a nota do primeiro trabalho: '))
t2 = float(input('Digite a nota do segundo trabalho: '))

provas = (p1 + p2)/2
trabalhos = (t1 + t2)
total = (provas + trabalhos)/2

print('A sua média foi {:.2f}'.format(total))

if total >= 6.0:
    print('Você passou!! PARABENS!!')
else:
    print('Você não passou!! ESTUDE MAIS!!')

print('Até o proximo semestre!!!')
