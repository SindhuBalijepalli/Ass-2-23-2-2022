a=[]
n=int(input('Enter n:'))
for i in  range(n):
    d=int(input())
    a.append(d)
print('mylist before reverse:',a)
a2=a
a2.reverse()
print('mylist after reverse',a2)

o/p:
enter n:3
mylist before reverse:[10,20,30]
mylist after reverse:[30,20,10]
