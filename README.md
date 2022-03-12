# Even-Subset-Sum-Problem
```python
x=int(input())
for i in range(x):
    n=int(input())
    a=list(map(int,input().split()))
    if n==1 and a[0]%2!=0:
        print(-1)
    else:
        check=0
        for ii in range(n):
            if a[ii]%2==0:
                print(1)
                print(ii+1)
                check=1
                break
        if check==0:
            print(2)
            print(1,2)
```
