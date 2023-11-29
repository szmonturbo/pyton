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





        Gra
        class Colors:
    RED = '\033[91m'
    GREEN = '\033[92m'
    YELLOW = '\033[93m'
    BLUE = '\033[94m'
    MAGENTA = '\033[95m'
    CYAN = '\033[96m'
    WHITE = '\033[97m'
    END = '\033[0m'

# wstep----------------
print(f' {Colors.BLUE}wybierz swoje imie:')
print('imie do wyboru -> Magik Krzys')
print('imie do wyboru -> Rzurzi')
print('imie do wyboru _> Jastrząb')

# inp--------------------
wybierz_imie_swej_postaci = input('wybierz imie swej postaci:')

# postacie--------------------
a = (input)
b = (input)
c = (input)
d = (input)

# Magik Krzys-------------------
if wybierz_imie_swej_postaci == 'Magik Krzys':
    print(f'{Colors.GREEN}Wybrane przez ciebie imie to Magik Krzys. Czy chcesz usłyszec w jakiej sytaucji sie znajduje aktualnie? ')
    
    # IFNORMACJE O Magiku Krzysiu
    opcja = input("Wybierz opcję (wpisz 'tak' lub 'nie'): ")
    if opcja == 'tak':
        print('Magik Krzys22 - tak walsnie sie nazywa dokladnie twoja postac. Pracuje ona aktualnie w żabce, lecz mysli nad zmiana pracy do firmy zajmujacej sie Vdolcami. Czy chcesz do niej przejsc?')
    elif opcja == 'nie':
        print('Niestety podjales zla decyzje. W tej grze wazne sa szczegoly. Bedzie ci pozniej trudno podejmowac decyzje, lecz wciaz masz szanse wygrac.')
    else:
        print('Wybierz dobra opcje!!!')

    # PRACA Magika Krzysia
    opcja = input("Wybierz opcję (wpisz 'tak' lub 'nie'): ")
    if opcja == 'tak':
        print('Postapiles ryzykownie, gdyz ta branza jest dosc ryzykowna. ')
        print('Juz pierwszego dnia odkryles potencjalne oszustwo. Postanowiles zbanować tą osobę. Twoj szef ma cie za nieodpowiedzialnego, wiec cie zwolnil. Wracajac do domu spotkal cie niespodziewana sytuacja. Napadli na ciebie drilowcy. Chcesz sie bic?')
    elif opcja == 'nie':
        print('Ze smutku przez fakt, ze odrzuciles decyzje postanawiasz wczesniej wrocic do domu. Po drodze napada na ciebie trzech osiedlowych Maciusiów2137. Zamierzasz sie bic?')
    else:
        print('Wybierz dobra opcje!!!')

    # BITWA
    opcja = input(f"Wybierz opcję (wpisz 'tak' lub 'nie'): {Colors.YELLOW} ")
    if opcja == 'tak':
        from random import randint, choice
        life = 10
        zlotowki = 4

        def atak_piescia():
            return randint(30, 50)

        def haranabuty():
            global zlotowki
            if zlotowki < 4:
                print("-" * 40)
                print("Nie masz wystarczającej ilości zlotwoek!")
                return 0
            zlotowki -= 4
            return randint(29, 29)

        def wybierz_atak():
            print('A - z piesci')
            print('B - haranabuty')
            co = input().upper()
            if co == 'A':
                return atak_piescia()
            elif co == 'B':
                return haranabuty()
            else:
                print("Nie wybrano dobrej akcji")
            return 0

        def MAciusie2137():
            opponents = [
                ["Kazama5", 100, 3, 0],
                ["Macius2137", 100, 3, 0]
            ]
            return choice(opponents)

        liczba_pokonanych_przeciwników = 0

        while life > 0:
            opponent = MAciusie2137()
            print("-" * 40)

            while opponent[1] > 0 and life > 0:
                print(f"Magik Krzys walczy teraz z {opponent[0]}")
                print(f"Przeciwnik ma {opponent[1]} HP i zadaje Ci {opponent[2]} obrażeń")

                life -= opponent[2]
                if life <= 0:
                    print(f"Masz {life} HP i {zlotowki} zlotowek")
                atak = wybierz_atak()
                opponent[1] -= atak
                print(f"Zadałeś {atak} obrażeń")

            if opponent[1] <= 0:
                print('Zabiłeś przeciwnika!!!')
                liczba_pokonanych_przeciwników += 1

        print("-" * 40)
        print("KONIEC GRY!")
        print(f"Zabiłeś {liczba_pokonanych_przeciwników} Maciusiów2137  ")
        if liczba_pokonanych_przeciwników == 0:
            print('Porazka!!! Przegrales!!!')
        elif liczba_pokonanych_przeciwników == 1:
            print('Brawoo,od teraz jestes kamim wyobraz to sobie sobie.')

# SMIERC PRZY USATWCE Magika Krzysia
    elif opcja == 'nie':
        print(f'{Colors.RED}Jestes skonczony... Maciusie2137 tanczą ci Lke.{Colors.RED}')
    else:
        print('Wybierz dobra opcje!!!')

# Rzurzi-------------------
if wybierz_imie_swej_postaci == 'Rzurzi':
    print(f'{Colors.GREEN}Wybrane przez ciebie imie to Rzurzi. Czy chcesz usłyszec jakie jest motto życiowe twoje i twoich braci? ')
    
    # IFNORMACJE O Braciach Rzurziego
    opcja = input("Wybierz opcję (wpisz 'tak' lub 'nie'): ")
    if opcja == 'tak':
        print('Magik Krzys22 -  brat brata strzela z gnata takie jest wasze motto. Pracujesz teraz w lewiatanie czy chciałbys pracować w monopolowym?')
       
    elif opcja == 'nie':
        print('Niestety podjales zla decyzje. W tej grze wazne sa szczegoly. Bedzie ci pozniej trudno podejmowac decyzje, lecz wciaz masz szanse wygrac.')
    else:
        print('Wybierz dobra opcje!!!')

    # PRACA Rzurziego
    opcja = input("Wybierz opcję (wpisz 'tak' lub 'nie'): ")
    if opcja == 'tak':
       
        print('Jeteś zadowolony z nowej pracy ale Juz pierwszego dnia był jakiś problem. Ktoś z pracowników ukradł cały dobytek z kasy. Szef oskarża ciebie i zwalnia. Po drodze do domu spotkałeś trzech kubusi')
        print(('Chcesz sie z nimi bić?'))
    elif opcja == 'nie':
        print('Ze smutku przez fakt, ze odrzuciles decyzje postanawiasz wczesniej wrocic do domu. Po drodze napada na ciebie trzech zdenerwowanych kubusiów Zamierzasz sie bic?')
    else:
        print('Wybierz dobra opcje!!!')

    # BITWA
    opcja = input(f"Wybierz opcję (wpisz 'tak' lub 'nie'): {Colors.YELLOW} ")
    if opcja == 'tak':
        from random import randint, choice
        life = 10
        zlotowki = 4

        def atak_butelkązwodka():
            return randint(30, 50)

        def pompaza200():
            global zlotowki
            if zlotowki < 4:
                print("-" * 40)
                print("Nie masz wystarczającej ilości zlotwoek!")
                return 0
            zlotowki -= 4
            return randint(29, 29)

        def wybierz_atak():
            print('A - z atak butelką wodki')
            print('B - pompa za 200')
            co = input().upper()
            if co == 'A':
                return atak_butelkązwodka()
            elif co == 'B':
                return pompaza200()
            else:
                print("Nie wybrano dobrej akcji")
            return 0

        def Kubusie():
            opponents = [
                ["Świr", 100, 3, 0],
                ["Spocuszek", 100, 3, 0]
            ]
            return choice(opponents)

        liczba_pokonanych_przeciwników = 0

        while life > 0:
            opponent = Kubusie()
            print("-" * 40)

            while opponent[1] > 0 and life > 0:
                print(f"Rzurzi walczy teraz z {opponent[0]}")
                print(f"Przeciwnik ma {opponent[1]} HP i zadaje Ci {opponent[2]} obrażeń")

                life -= opponent[2]
                if life <= 0:
                    print(f"Masz {life} HP i {zlotowki} zlotowek")
                atak = wybierz_atak()
                opponent[1] -= atak
                print(f"Zadałeś {atak} obrażeń")

            if opponent[1] <= 0:
                print('Zabiłeś przeciwnika!!!')
                liczba_pokonanych_przeciwników += 1

        print("-" * 40)
        print("KONIEC GRY!")
        print(f"Zabiłeś {liczba_pokonanych_przeciwników} Kubusiów  ")
        if liczba_pokonanych_przeciwników == 0:
            print('Porazka!!! Przegrales!!!')
        elif liczba_pokonanych_przeciwników == 1:
            print('Brawoo, odtad zyjesz szczęśliwy ze swoimi braćmi.')

# SMIERC PRZY USATWCE Rzurziego
    elif opcja == 'nie':
        print(f'{Colors.RED}Jestes skonczony... Kubusie plują na ciebie.{Colors.RED}')
    else:
        print('Wybierz dobra opcje!!!')
# ---------------------------------------------------------
## Jastrząb
if wybierz_imie_swej_postaci == 'Jastrząb':
    print(f'{Colors.GREEN}Wybrane przez ciebie imie to Jastrząb. Czy chcesz usłyszec w jakiej sytaucji sie znajduje aktualnie? ')
    
    # IFNORMACJE O JAstrzębiu
    opcja = input("Wybierz opcję (wpisz 'tak' lub 'nie'): ")
    if opcja == 'tak':
        print('Jastrząb Jastrzębski - tak walsnie sie nazywa dokladnie twoja postac. Nie ma nic do zjedzenie w domu. Jesteś w parku masz tu zostać czy iść do sklepu  ?')
    elif opcja == 'nie':
        print('Niestety podjales zla decyzje. W tej grze wazne sa szczegoly. Bedzie ci pozniej trudno podejmowac decyzje, lecz wciaz masz szanse wygrac. Jesteś głodny gdzie wolisz iść')
    else:
        print('Wybierz dobra opcje!!!')

    # PRACA Jastrzębia
    opcja = input("Wybierz opcję (wpisz 'zostac' lub 'do sklepu'): ")
    if opcja == 'do sklepu':
        print('Jest 23 grudnia i promocja na Karpia idziesz do działu mięsnego gdzie toczy się wojna o karpie. Cudem udało ci się uciec z jednym lecz chwile przed Kasą zatrzymało cie trzech dziadków. Chcesz sie z nimi bić? ')
        print('Chcesz sie z nimi bić?')
    elif opcja == 'zostac':
        print('Podczas odpoczywania zaatakowały cię agresywne trzy kidosy. Jeden Kopnoł cie w kolano.')
        print('Chcesz sie z nimi bić?')
    else:
        print('Wybierz dobra opcje!!!')

    # BITWA
opcja = input(f"Wybierz opcję (wpisz 'tak' lub 'nie'): {Colors.YELLOW} ")
if opcja == 'tak':
        from random import randint, choice
        life = 10
        zlotowki = 4

        def Zbażanta():
            return randint(30, 50)

        def WózekSklepowy():
            global zlotowki
            if zlotowki < 4:
                print("-" * 40)
                print("Nie masz wystarczającej ilości zlotwoek!")
                return 0
            zlotowki -= 4
            return randint(29, 29)

        def wybierz_atak():
            print('A - z bażanta')
            print('B - wuskiem sklepowym')
            co = input().upper()
            if co == 'A':
                return Zbażanta()
            elif co == 'B':
                return WózekSklepowy()
            else:
                print("Nie wybrano dobrej akcji")
            return 0

        def Kidoski():
            opponents = [
                ["Kacperek", 100, 3, 0],
                ["Karzełek", 100, 3, 0]
            ]
            return choice(opponents)

        liczba_pokonanych_przeciwników = 0

        while life > 0:
            opponent = Kidoski()
            print("-" * 40)

            while opponent[1] > 0 and life > 0:
                print(f"Jastrząb walczy teraz z {opponent[0]}")
                print(f"Przeciwnik ma {opponent[1]} HP i zadaje Ci {opponent[2]} obrażeń")

                life -= opponent[2]
                if life <= 0:
                    print(f"Masz {life} HP i {zlotowki} zlotowek")
                atak = wybierz_atak()
                opponent[1] -= atak
                print(f"Zadałeś {atak} obrażeń")

            if opponent[1] <= 0:
                print('Zabiłeś przeciwnika!!!')
                liczba_pokonanych_przeciwników += 1

        print("-" * 40)
        print("KONIEC GRY!")
        print(f"Zabiłeś {liczba_pokonanych_przeciwników} Kidosków  ")
        if liczba_pokonanych_przeciwników == 0:
            print('Porazka!!! Przegrales!!!')
        elif liczba_pokonanych_przeciwników == 1:
            print('Brawoo,wbiłes nierealną range.')

# SMIERC PRZY USATWCE Jastrzębia
elif opcja == 'nie':
        print(f'{Colors.RED}Jestes skonczony... Kidoski okradają cie.{Colors.RED}')
else:
        print('Wybierz dobra opcje!!!')

