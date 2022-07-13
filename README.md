# python
THIS REPOSITORY IS CREATED TO STORE MY PYTHON PROJECTS & IDEAS.

# how to take multiple inputs:
# 1
x = input('enter values : ').split(',')
print(x)
# ['3', ' 4', ' 5']

# 2 - if you want the value to be in integer format split function won't work.
l = []
for i in range(5):
    x = int(input('enter the value :'))
    l.append(x)
print(l)
# 3
