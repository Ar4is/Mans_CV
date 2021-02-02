# Mans_CV

## Citāts
*Mans mīļākais citāts,kurš vienmēr pirmais ir atmiņa runājot par citātiem.*
**“Atstāj savu prātu.” Kļūsti amorfs, bezveidīgs kā ūdens. Kad ūdeni lej tasē, tā kļūst par tasi. Kad ūdeni lej tējkannā, tā kļūst par tējkannu. Kad ūdeni ielej pudelē, tas kļūst par pudeli. Ūdens var plūst, bet var sagraut. Esi ūdens, mans draugs.**

## Koda gabals.(No Python)
`''' Kvadrātvienādojuma a x2 + b x + c = 0 sakņu rēķināšana:
D = b2 - 4 a c ,ja D > 0,tad divas saknes,
D = 0, tad viena sakne,
D < 0, tad sakņu nav.


Izveideoja: Artūrs Vaļuks.
'''

from math import sqrt              #Kvadrātsaknes  funkcijas importēšana

print('Kvadrātvienādojuma a x2 + b x + c = 0 sakņu reiķināšana/n')
a = float(input('Ievadiet a, decimaldaļas skaitli: '))
b = float(input('Ievadiet b, decimaldaļas skaitli: '))
c = float(input('Ievadiet c, decimaldaļas skaitli: '))



#Diskriminanta rēķināšana

D =b**2 - 4*a*c   #Diskriminanta formula


#Sakņu rēķināšana

if D == 0 : #Salīdzina diskriminants vienāds ar 0
   x = -(b)/(2*a)     #formula
   print('Diskriminants D = 0, viena sakne,',x,)
else :
    if D > 0 :   #Salīdzina diskriminants lielāks par  0
        x1 = (-(b) + sqrt(D))/(2 * a)    # 1. saknes rēķināšana
        x2 = (-(b) - sqrt(D))/(2 * a)   # 2. saknes rēķināšana


        # 2 sakņu izvade

        print('Diskriminants D > 0, divas saknes x1 =',x1,' un x2 =',x2,)
    else :       #Diskriminants mazāks par 0
        print('Diskriminants D < 0, tad sakņu nav.')
`
## Bilde
![Nav lejuplādēts](data:image/jpeg;base64,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)
![Nav lejupielādējusies](me1.jpg)

## Saraksts
1. Es nodarbojos ar Breiku,jau 8 gadus.
2. Es spēlēju ģitāru no 12 gadiem.
3. Mācos RVT
4. Dzīvoju Tukumā

- [ ] Sociāli aktīvs
- [x] Esmu ambiciozs
- [ ] Draudzīgs
- [x] Regulāri nodarbojos ar sportu

## Tabula
| Nodarbes | Pritoritāte 5 baļu sistēmā |
| Dejošana | 4 |
| mācības | 3 |
| Draugi | 4 | 
| Pašattīstība | 3 |
| līdzekļu peļņa | 3 |
| Atpūta| 3 |
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
😃😃
😉😉
😀😀
