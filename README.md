# MissingNumber

```
def missingnumber(n, arr):
  
  sum = n*(n+1)/2
  
  tmp = 0
  
  for i in range(n-1):
    
    tmp += arr[i]
  
  res = sum - tmp
  
  return (int)(res)
  
n = int(input())

arr = list(map(int, input().split()))

final_res = missingnumber(n,arr)

print(final_res)
```
