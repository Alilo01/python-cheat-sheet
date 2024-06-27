بالطبع! إليك مجموعة من الأكواد الشبيهة بـ `numbers.append(num)` في Python، والتي تتعامل مع القوائم بطرق مختلفة:

### إنشاء قائمة جديدة بعدد معين من العناصر الفارغة
```python
n = 5
numbers = [0] * n
print(numbers)  # Output: [0, 0, 0, 0, 0]
```

### إضافة أكثر من عنصر في نفس الوقت
```python
numbers = [1, 2, 3]
numbers.extend([4, 5, 6])
print(numbers)  # Output: [1, 2, 3, 4, 5, 6]
```

### إنشاء قائمة باستخدام التكرار
```python
n = 5
numbers = [i for i in range(n)]
print(numbers)  # Output: [0, 1, 2, 3, 4]
```

### إضافة عناصر من قائمة إلى قائمة أخرى
```python
numbers = [1, 2, 3]
other_numbers = [4, 5, 6]
numbers += other_numbers
print(numbers)  # Output: [1, 2, 3, 4, 5, 6]
```

### إزالة عنصر معين من القائمة
```python
numbers = [1, 2, 3, 4, 5]
numbers.remove(3)
print(numbers)  # Output: [1, 2, 4, 5]
```

### إيجاد الفهرس (الموقع) لعنصر معين في القائمة
```python
numbers = [1, 2, 3, 4, 5]
index = numbers.index(3)
print(index)  # Output: 2
```

### تعدد الأبعاد (قائمة داخل قائمة)
```python
matrix = [[1, 2], [3, 4], [5, 6]]
print(matrix)  # Output: [[1, 2], [3, 4], [5, 6]]
```

### إدراج عنصر في مكان محدد
```python
numbers = [1, 2, 4, 5]
numbers.insert(2, 3)
print(numbers)  # Output: [1, 2, 3, 4, 5]
```

### تفريغ قائمة
```python
numbers = [1, 2, 3, 4, 5]
numbers.clear()
print(numbers)  # Output: []
```

### عدّ تكرار عنصر معين في القائمة
```python
numbers = [1, 2, 3, 2, 4, 2, 5]
count = numbers.count(2)
print(count)  # Output: 3
```

### ترتيب العناصر في القائمة
```python
numbers = [3, 1, 4, 1, 5, 9, 2]
numbers.sort()
print(numbers)  # Output: [1, 1, 2, 3, 4, 5, 9]
```

### ترتيب العناصر في القائمة بترتيب عكسي
```python
numbers = [3, 1, 4, 1, 5, 9, 2]
numbers.sort(reverse=True)
print(numbers)  # Output: [9, 5, 4, 3, 2, 1, 1]
```

### عكس ترتيب العناصر في القائمة
```python
numbers = [1, 2, 3, 4, 5]
numbers.reverse()
print(numbers)  # Output: [5, 4, 3, 2, 1]
```

### نسخ قائمة
```python
numbers = [1, 2, 3, 4, 5]
numbers_copy = numbers.copy()
print(numbers_copy)  # Output: [1, 2, 3, 4, 5]
```

### حذف عنصر من القائمة باستخدام الفهرس
```python
numbers = [1, 2, 3, 4, 5]
del numbers[2]
print(numbers)  # Output: [1, 2, 4, 5]
```

### إزالة آخر عنصر من القائمة وإرجاعه
```python
numbers = [1, 2, 3, 4, 5]
last = numbers.pop()
print(last)  # Output: 5
print(numbers)  # Output: [1, 2, 3, 4]
```

### إزالة عنصر من القائمة باستخدام الفهرس وإرجاعه
```python
numbers = [1, 2, 3, 4, 5]
element = numbers.pop(2)
print(element)  # Output: 3
print(numbers)  # Output: [1, 2, 4, 5]
```

هذه العمليات تغطي معظم الوظائف التي قد تحتاجها عند التعامل مع القوائم في Python.
