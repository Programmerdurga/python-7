# python-7
bank program
'''
enter the total120
enter the amount withdraw 90
29.5'''
b=int(input("enter the total"))
w=int(input("enter the amount withdraw "))
if w%5==0 and w<b:
    print(b-w-0.50)
else:
    print(b)
