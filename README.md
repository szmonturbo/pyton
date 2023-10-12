a = float(input("a = "))
b = float(input("b = "))
c = float(input("c = "))
if a + b >= c and a + c >=b and b + c >=a:
    print("to jest tr")
    p = 1/2(a+b+c)
    P = math.sqrt(p*(p-a)*(p-b)*(p-c))
    print(f"pole powierzchni tr= {P}")
else:
    print("nie jest")
    if a**2 + b**2 == c**2 or c**2 + b**2 == a**2 or a**2 + c**2 == b**2
        print ("jest prost")
    else:
        print("nie jest pro")
else:                     



import math

#Napisz program który na każde zadane pytanie odpowiada “perhaps”

while True:
    print("Zadaj mi pytanie")
    x  = input("Pytanie...")
    print("Perhaps")

#Napiszmy program który wyświetli nam wszystkie liczby podzielne przez 9. Do wartości podanej przez użytkownika.

inp = int(input("inp = "))
while 0 <= inp:
    if inp % 9 == 0:
        print(inp)
    inp -= 1

#Napisz program który z wypisze wszystkie liczby które NIE są podzielne przez 3.  Do wartości podanej przez użytkownika.

inp = int(input("inp = "))
while 0 <= inp:
    if inp % 3 != 0:
        print(inp)
    inp -= 1

#Napisz program który wyświetli n potęg liczby 2.

n = int(input("n = "))
while 0 <= n:
    print(2**n)
    n -= 1

#Zsumuj wszystkie liczby które są są podzielne przez 5 do wartości podanej przez użytkownika. 

inp = int(input("inp = "))
dzielnik_1 = int(input("dzielnik_1 = "))
dzielnik_2 = int(input("dzielnik_2 = "))
suma = 0
suma_liczb = 0
while 0 <= inp:
    if inp %dzielnik_1 == 0 and  inp % dzielnik_2 == 0
        suma += 1
        suma_liczb = suma_liczb + inp
    inp -= 1
print('Tyle jest liczb ', suma)
print('suma_liczb ',   suma_liczb)



1

lista = []

while true:

    inp = input[]

    if inp == 'stop':

        breakinp = float(inp)

        if inp >= 1 and inp <=200:

            lista.append(inp)

        else:

            print("liczba po za wymaganym zakresem liczbowym")

            

print(lista)











2

nowa lista = []

i = 0

while i < len(lista) :

    if lista[i] > 50 and lista[i] < 70 and lista [i] & 2 == 0:

        nowa_lista.append(lista[i])

        i += 1

        print(nowa_lista)

        





3

oceny = []

while true:

    inp = input()

    if inp == "stop" :

        break

    inp = float(inp)

    if inp <= 6 and inp >= 1:

        oceny.append(inp)

    else:

        print("podales złe liczby Nobie!")

        print(sum(oceny)/len(oceny)

              







4

inp = input()

i = 0

while i < len(inp):

print(inp[i])

i <= 1import math


while True:
    print("------------------------------------------------")
    print("Pc Kuli - 1 | V Kuli - 2")
    print("Pc Walca - 3 | pc szesciana - 4")
    print("pc prostopadloscianu - 5 | ")
    print("pc ostroslupa - 6 | ")
    print("pc graniastoslupa - 7")
    print("8 - wyjdz z programu")
    print("------------------------------------------------")
    inp = input("Podaj liczbe: ")
    if "1" == inp:
        r = float(input("r = "))
        Pc_kuli = 4/3*math.pi*pow(r,3)
        print(f"Pc-Kuli = {Pc_kuli}")
    elif "2" == inp:
        r = float(input("r = "))
        V_kuli = 4*math.pi*pow(r,2)
        print(f"V kuli = {V_kuli}")        
    elif "3" == inp:
        r = float(input("r = "))
        h = float(input("h = "))
        Pc_walca = 2*math.pi*h+2*math.pi*r*pow(2)
        print(f"Pc walca = {Pc_walca}")
    elif "4" == inp:
        a = float(input("a = "))
        Pc_szesciana = 6*(a**2)
        print(f"Pc szesciana = {Pc_szesciana}")
    elif "5" == inp:
        a = float(input("a = "))
        b = float(input("b = "))
        c = float(input("c = "))
        Pc_prostopadlosciana = (2*a*b)+(2*b*c)+(2*a*c)
        print(f"pc prostopadlosciana = {Pc_prostopadlosciana}")
    elif "6" == inp:
        Pp = float(input("Pp = "))
        Pb = float(input("Pb = "))
        Pc_ostroslupa = Pp+Pb
        print(f"Pc ostroslupa = {Pc_ostroslupa}")
    elif "7" == inp:
        Pp = float(input("Pp = "))
        Pb = float(input("Pb = "))
        Pc_graniastoslupa = 2*(Pp+Pb)
        print(f"Pc graniastoslupa = {Pc_graniastoslupa}")
    elif "8" == inp:
        break
