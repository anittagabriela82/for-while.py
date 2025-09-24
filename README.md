# for-while.py
valor = int(input("digite um valor de 0-5: "))
while True:
    if valor < 0:
        valor = int(input("valor incorreto, digite novamente: "))
    elif valor > 5 :
        valor = int(input("digite um valor valido de 0-5: "))
    else:
        print("valor correto!")
        break
