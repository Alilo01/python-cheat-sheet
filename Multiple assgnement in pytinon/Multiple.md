

```python
# التعيين المتعدد في Python
# Multiple assignment in Python

# تعيين قيم لعدة متغيرات في سطر واحد
# Assigning values to multiple variables in a single line
x, y, z = 10, 20, 30

# طباعة القيم للتحقق
# Printing values to verify
print("x =", x)
print("y =", y)
print("z =", z)
```

### Explication (شرح):
- في هذا المثال، قمنا بتعريف ثلاث متغيرات `x`، `y`، و `z` في سطر واحد، وقمنا بتعيين قيم `10`، `20`، و `30` لكل منها.
- تم استخدام الدالة `print` لطباعة قيم المتغيرات للتحقق من صحة التعيين المتعدد.

### Swapping Variables (تبديل القيم):
يمكن أيضًا استخدام التعيين المتعدد لتبديل قيم المتغيرات بسهولة، كما يلي:

```python
# تبديل قيم المتغيرات باستخدام التعيين المتعدد
# Swapping variables using multiple assignment
a = 5
b = 10

print("قبل التبديل:")
print("a =", a)
print("b =", b)

a, b = b, a

print("\nبعد التبديل:")
print("a =", a)
print("b =", b)
```

### Unpacking (فك الحزم):
يمكن استخدام التعيين المتعدد أيضًا لفك حزم العناصر من قوائم أو طوابير إلى متغيرات فردية، كما في المثال التالي:

```python
# فك حزم العناصر من قائمة إلى متغيرات فردية
# Unpacking elements from a list into individual variables
numbers = [1, 2, 3]

x, y, z = numbers

print("x =", x)
print("y =", y)
print("z =", z)
```

### Ignoring Values (تجاهل القيم):
يمكنك استخدام `_` لتجاهل القيم أثناء التعيين المتعدد إذا لم تحتاج إلى استخدام بعض القيم، مثل هذا:

```python
# تجاهل القيم غير المرغوب فيها باستخدام `_`
# Ignoring unwanted values using `_`
a, _, c = (1, 2, 3)

print("a =", a)
print("c =", c)
```

هذه هي بعض الاستخدامات الشائعة للتعيين المتعدد في Python، مما يجعل الكود أكثر إيجازًا وسهولة في القراءة والصيانة.
