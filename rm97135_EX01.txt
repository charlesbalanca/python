faturamento = float(input('quanto foi o faturamento do ano?'))

print(faturamento)

print('por favor selecione o plano')
print('digite 1 para plano Basic com 30% de bonus')
print('digite 2 para plano Silver com 20% de bonus')
print('digite 3 para plano Gold com 10% de bonus')
print('digite 4 para plano Platinum com 5% de bonus')

plano = int(input('qual o plano?'))

if plano==1:
    print(faturamento*0.3)
elif plano==2:
    print(faturamento*0.2)
elif plano==3:
    print(faturamento*0.1)
elif plano==4:
    print(faturamento*0.05)
else plano>4:
    print("plano inexistente")
