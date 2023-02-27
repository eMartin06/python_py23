szam=int(input('Kérek egy páros számot! '))

while szam%2 !=0:
    szam=int(input('Kérek egy páros számot! '))
    print('Ez nem egy páros szám!')
    
if szam%2 ==0:
        print('Ez egy páros szám.')