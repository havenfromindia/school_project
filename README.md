# school_project
codes from school AI text book
 # string.isalpha()
trial = input('enter the value : ')
search = trial.isalpha()
non1 = 3 > 2
non2 = 3 < 2
if search == non1 :
    print(trial, 'is an alphabet')
elif search == non2 :
    print(trial, 'is not an alphabet')
# u is an alphabet
# 7 is not an alphabet
print(search)

name = "Monica"
print(name.isalpha())

year = 2020
if year % 4 == 0:
    print(year, 'is a leap year')
else:
    print(year, 'is not a leap year')

n = 0
m = 77
p = 4

if n > m and n > p:
    largest = n
elif m > n and m > p:
    largest = m
elif p > n and p > m:
    largest = p
print(largest, 'is the largest number')

print(input('enter your name : '), input('enter your class : '))

a = int(input('enter the 1st value : '))
if a > 5:
    print(a, 'is positive')
elif a < 5:
    print(a, 'is negative')
elif a == 0:
    print(a, 'is zero')

b = int(input('enter the 2nd value : '))
c = int(input('enter the 2nd value : '))
x = a + b + c
print('sum is', x)
print('avg is', x//3)
