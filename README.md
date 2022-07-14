# Ass-2-14-7-22
Assignment-2
n=int(input())
l=list(map(int,input().split()))
print(max(set(l),key=l.count))
