# bubble_sorttxd


```python
lista = [101,88,1,98,45,7777,6,9,1,34,4,5,6,7,1001]

print(f"Össze vissza: {lista}\n")

def bubble_sort(l):
    for i in range(len(l)-1):
        for index in range(len(l)-i-1):
            if l[index] > l[index+1]:
                    l[index], l[index+1] = l[index+1], l[index]
    return l
        

print(f"Rendezett: {bubble_sort(lista)}")
```
