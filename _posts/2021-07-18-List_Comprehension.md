기존의 리스트를 사용해서 다른 리스트를 만드는 기법.

아무래도 기존의 리스트에 append를 해주는 것 보다 메모리를 덜 차지하다보니 속도가 더 빠름.


```python
fruits = ['apple', 'banana', 'orange', 'melon']

new_fruits = []

for fruit in fruits :
	new_fruits.append(fruit)

print (new_fruits)
```

    ['apple', 'banana', 'orange', 'melon']
    


```python
fruits = [ 'apple' , 'banana' , 'orange' , 'melon']

new_fruits = [fruit for fruit in fruits]

print (new_fruits)
```

    ['apple', 'banana', 'orange', 'melon']
    
