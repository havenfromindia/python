# python
THIS REPOSITORY IS CREATED TO STORE MY PYTHON PROJECTS & IDEAS.

#1
#input function
print('sum =',input('1st : ')+input('2nd : '))

#2
a = 5
b = 10
print (a,b)
#(5, 10)
# same formula with xor function
# xor reduse bits
a = a ^ b
b = a ^ b
a = a ^ b
print (a,b)
# (10, 5)

#3
#even number finding system
#better than the other even number finding system(before + dictionary)
use = input('to check whether the number is odd/even : ')
if use % 2 == 1:
    dict = {use : 'odd'}
    print (dict)
if use % 2 == 0:
    dict = {use : 'even'}
    print (dict)
#to check whether the number is odd/even : 6
#{6: 'even'}
