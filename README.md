# python-2
Mukesh and his friends have set out on a vacation to Coorg. They have booked accommodation in a resort and the resort authorities organize Campfires every night as a part of their daily activities

#CODE

from functools import reduce
n=int(input())
arr=[]
n1=list(input().split())
n1=[int(e) for e in n1]
if(n%2==0):
for i in range(0,n-1,2): 
if(n1[i]>n1[i+1]):
arr.append(n1[i+1])
else:
arr.append(n1[i]])
blen=reduce(lambda x,y:x+y, arr)
print(blen)
