# CricketRanking
# cook your dish here
t=int(input())
while t:
    a=list(map(int,input().split()))
    b=list(map(int,input().split()))
    c=0
    d=0
    for i in range(len(a) and len(b)):
        if(a[i]>b[i]):
            c+=1
        else:
            d+=1
    if(c>d):
        print("A")
    else:
        print("B")
    t-=1
