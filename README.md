# 14-02-2022-assignment-2
#sum the given number digits
n=int(input('enter the number:'))
num=n
rev=0
while n>0:
    rem=n%10
    rev=rev+rem
    n=n//10
print(rev)


output:
====================== RESTART: C:/Python37/sum dig.py ======================
enter the number:369
18
>>> 
