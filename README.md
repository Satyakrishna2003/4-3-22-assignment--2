# 4-3-22-assignment--2
n=int(input())
l=input().split()
t=[]
for i in l:
    t.append(int(i))
x=[]
for i in t:
    if i not in x:
        x.append(i)
print(x)
x.sort(reverse=True)
print(x)
print(x[1])

OUTPUT:-
6
7 8 2 4 6 8 9
[7, 8, 2, 4, 6, 9]
[9, 8, 7, 6, 4, 2]
8
