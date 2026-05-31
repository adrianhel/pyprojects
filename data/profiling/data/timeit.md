# Модуль `timeit` 

### [Назад в Профилирование ⤶](/data/profiling/profiling.md)

---

Модуль `timeit` предназначен для точного измерения времени выполнения небольших фрагментов кода.

### Пример измерения времени выполнения выражения

```python
import timeit

result = timeit.timeit("sum([i for i in range(100)])", number=10000)
print(result)
```