# AlgorytmRSA

 #Algorytm sprawdzający czy wpisana przez usera liczba jest pierwsza

a = int(input())
def czypierwsza(a):
    for i in range(2, a):
       if a%i == 0:
            return False
    else:
        return True
print(czypierwsza(a))

#Algorytm generujący najmniejszą liczbę pierwszą większą od zadanego n

n = int(input())
liczba = 0
m = n + 1
for i in range(2, n):
    if m%i == 0:
       m+= 1
    else:
       liczba = m
print(liczba)
        
#Algorytm sprawdzający, czy dwie wpisane liczby są względnie pierwsze

a = int(input())
b = int(input())
def czywzgledne(a, b):
    for i in range(2, b):
        if a%i == 0 and b%i == 0:
            return False
    else :
        return True
print(czywzgledne(a, b))
