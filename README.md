# python
THIS REPOSITORY IS CREATED TO STORE MY PYTHON PROJECTS & IDEAS.

#to print
#cody banks banks banks banks banks
#cody banks banks banks banks banks
#etc
print()
j = 1
x = 1
while j <= 5:
    print('cody', end='')
    while x <= 5:
        print(' banks',end='')
        x = x + 1
    j = j + 1
    print()
#cody banks banks banks banks banks
#cody
#cody
#cody
#cody

#***********************----IMPROVED------*******************************************

#moved x = 1  
j = 1
while j <= 5:
    print('cody',end='')
    x = 1
    while x <= 5:
        print(' banks',end='')
        x = x + 1
    j = j + 1
    print()

#cody banks banks banks banks banks
#cody banks banks banks banks banks
#cody banks banks banks banks banks
#cody banks banks banks banks banks
#cody banks banks banks banks banks


# 2) print values from 1 to 100 which are divisible by 3 & 5.
r = list(range(0,101,3))
y = list(range(0,101,5))
print(r)
print(y)

print()

#using while loop.
i = 1
while i <= 100:
    if i%3 == 0:
        print(i)
    if i%5 == 0:
        print(i)
    i = i + 1
#3
#5
#6
#9
#10
#12 etc
#TILL 100

#******************-----------A BETTER WAY OF INTERPRITING--------------*******************
test3 = []
test5 = []
i = 1
while i <= 100:
    if i%3 == 0:
        test3.append(i)
    if i%5 == 0:
        test5.append(i)
    i = i + 1
print(test3)
print(test5)
#[3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 51, 54, 57, 60, 63, 66, 69, 72, 75, 78, 81, 84, 87, 90, 93, 96, 99]
#[5, 10, 15, 20, 25, 30, 35, 40, 45, 50, 55, 60, 65, 70, 75, 80, 85, 90, 95, 100]

