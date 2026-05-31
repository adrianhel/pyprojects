# Модуль `timeit` предназначен для точного измерения времени выполнения небольших фрагментов кода.

## База
```python
import timeit

result = timeit.timeit("sum([i for i in range(100)])", number=10000)
print(result)
```