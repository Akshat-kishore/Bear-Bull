# Bear-Bull
# cook your dish here
a=int(input())
for i in range(a):
    x, y = map(int, input().split())
    if (x>y):
        print("LOSS")
        continue
    if (x==y):
        print("NEUTRAL")
        continue
    else:
        print("PROFIT")
        continue
