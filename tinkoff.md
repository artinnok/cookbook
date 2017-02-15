# Тиньков банк

1. Опиши Python как язык и сравни его с другими языками программирования.
2. Что такое Garbage Collector? Для чего он нужен?
3. Напиши функцию, которая переворачивает строку. Какие у нее могут быть ошибки?
4. Напиши декоратор. Напиши декоратор, который принимает аргументы

---------

```
list = ['a', 'b', 'c', 'd']
print(list[10:])
```

---------

```
list = [[]] * 5
list[0].append(4)
list[1].append(5)
print(list)
```

---------

```
def hello(l):
  l.append(5)
  
list = [1, 2, 3]
hello(list)
list.append(4)
print(list)
```

---------

```
def multipliers():
  return [lambda x: i * x for i in range(4)]
  
print([m(2) for m in multipliers()]
```
