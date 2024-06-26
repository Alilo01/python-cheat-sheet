نوع التحويل (Type casting) في Python يشير إلى تحويل قيمة من نوع بيانات إلى نوع بيانات آخر. هذا يمكن أن يكون مفيدًا عند الحاجة إلى تغيير النوع لتناسب العمليات المختلفة التي يتعامل معها البرنامج. إليك بعض الأمثلة على نوع التحويل في Python:

### 1. تحويل إلى نوع الصحائف (Strings)

لتحويل قيم إلى نوع الصحائف (strings)، يمكنك استخدام دالة `str()`:

```python
num = 123
num_str = str(num)
print(num_str)  # الطباعة: "123"
```

### 2. تحويل إلى نوع الأعداد الصحيحة (Integers)

لتحويل قيم إلى نوع الأعداد الصحيحة (integers)، يمكنك استخدام دالة `int()`:

```python
num_str = "456"
num = int(num_str)
print(num)  # الطباعة: 456
```

### 3. تحويل إلى نوع الأعداد العشرية (Floats)

لتحويل قيم إلى نوع الأعداد العشرية (floats)، يمكنك استخدام دالة `float()`:

```python
num_str = "3.14"
num = float(num_str)
print(num)  # الطباعة: 3.14
```

### 4. تحويل إلى نوع القائمة (Lists)

لتحويل قيم إلى نوع القائمة (lists)، يمكنك استخدام دالة `list()`:

```python
text = "Hello"
list_text = list(text)
print(list_text)  # الطباعة: ['H', 'e', 'l', 'l', 'o']
```

### 5. تحويل إلى نوع الطابور (Tuples)

لتحويل قيم إلى نوع الطابور (tuples)، يمكنك استخدام دالة `tuple()`:

```python
list_text = ['H', 'e', 'l', 'l', 'o']
tuple_text = tuple(list_text)
print(tuple_text)  # الطباعة: ('H', 'e', 'l', 'l', 'o')
```

### 6. تحويل إلى نوع المجموعة (Sets)

لتحويل قيم إلى نوع المجموعة (sets)، يمكنك استخدام دالة `set()`:

```python
numbers = [1, 2, 3, 3, 4, 5]
set_numbers = set(numbers)
print(set_numbers)  # الطباعة: {1, 2, 3, 4, 5}
```

### 7. تحويل إلى نوع القاموس (Dictionaries)

لتحويل قيم إلى نوع القاموس (dictionaries)، يمكنك استخدام دالة `dict()`:

```python
tuple_pair = (('name', 'Alice'), ('age', 25))
dict_pair = dict(tuple_pair)
print(dict_pair)  # الطباعة: {'name': 'Alice', 'age': 25}
```

هذه هي بعض الأمثلة على كيفية استخدام تحويل الأنواع في Python لتعديل نوع البيانات وفقًا لاحتياجات البرنامج.
