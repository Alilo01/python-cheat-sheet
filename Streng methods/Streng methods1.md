```python
name = "Bro"

# طول السلسلة
print(len(name))  # الطباعة: 3

# البحث عن أول حرف "o"
print(name.find("o"))  # الطباعة: 1

# تحويل أول حرف إلى حرف كبير والبقية إلى صغيرة
print(name.capitalize())  # الطباعة: Bro

# تحويل كل الأحرف إلى أحرف كبيرة
print(name.upper())  # الطباعة: BRO

# تحويل كل الأحرف إلى أحرف صغيرة
print(name.lower())  # الطباعة: bro

# التحقق مما إذا كانت السلسلة تحتوي على أرقام فقط
print(name.isdigit())  # الطباعة: False

# التحقق مما إذا كانت السلسلة تحتوي على حروف فقط
print(name.isalpha())  # الطباعة: True

# عدد مرات ظهور حرف "o" في السلسلة
print(name.count("o"))  # الطباعة: 1

# استبدال كل حرف "o" بحرف "a"
print(name.replace("o", "a"))  # الطباعة: Bra

# طباعة السلسلة ثلاث مرات متتالية
print(name * 3)  # الطباعة: BroBroBro
```
