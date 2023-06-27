# Perfect-trio
t=int(input())
while t:
    a,b,c=map(int,input().split())
    if(((a+b)==c) or ((b+c)==a) or ((a+c)==b)):
        print("YES")
    else:
        print("NO")
    t-=1
