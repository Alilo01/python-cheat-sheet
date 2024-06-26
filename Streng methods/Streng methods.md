في Python، هناك العديد من الطرق والوظائف المدمجة (methods) التي يمكن استخدامها للتعامل مع النصوص (strings). سأقدم لك بعض الأمثلة على أهم هذه الوظائف باللغة العربية:

### 1. تحويل الحروف

يمكنك استخدام الوظائف التالية لتحويل الحروف في النص:

- **upper()**: تحويل النص إلى حروف كبيرة.
  
  ```python
  text = "Hello, World!"
  print(text.upper())  # الطباعة: HELLO, WORLD!
  ```

- **lower()**: تحويل النص إلى حروف صغيرة.
  
  ```python
  text = "Hello, World!"
  print(text.lower())  # الطباعة: hello, world!
  ```

### 2. البحث والاستبدال

يمكنك استخدام الوظائف التالية للبحث عن نصوص محددة داخل النص واستبدالها:

- **find()**: البحث عن موضع أول حرف في النص. إذا لم يتم العثور على النص، فإن الدالة تُعيد -1.
  
  ```python
  text = "Hello, World!"
  print(text.find("World"))  # الطباعة: 7
  ```

- **replace()**: استبدال جميع حالات النص بنص آخر.
  
  ```python
  text = "Hello, World!"
  new_text = text.replace("World", "Python")
  print(new_text)  # الطباعة: Hello, Python!
  ```

### 3. التقسيم والانضمام

يمكنك استخدام الوظائف التالية لتقسيم النص إلى أجزاء أو لدمج أجزاء من النص:

- **split()**: تقسيم النص إلى قائمة من الأجزاء باستخدام فاصل معين.
  
  ```python
  text = "apple,banana,cherry"
  fruits = text.split(",")
  print(fruits)  # الطباعة: ['apple', 'banana', 'cherry']
  ```

- **join()**: دمج قائمة من النصوص في نص واحد، باستخدام فاصل معين.
  
  ```python
  fruits = ['apple', 'banana', 'cherry']
  text = ",".join(fruits)
  print(text)  # الطباعة: apple,banana,cherry
  ```

### 4. الفحص والتحقق

يمكنك استخدام الوظائف التالية لفحص النص والتأكد من خصائصه:

- **startswith()**: التحقق مما إذا كان النص يبدأ بنص معين.
  
  ```python
  text = "Hello, World!"
  print(text.startswith("Hello"))  # الطباعة: True
  ```

- **endswith()**: التحقق مما إذا كان النص ينتهي بنص معين.
  
  ```python
  text = "Hello, World!"
  print(text.endswith("!"))  # الطباعة: True
  ```

هذه بعض الوظائف الأساسية التي تساعدك في التعامل مع النصوص في Python. يمكنك استخدامها بشكل فعال لإجراء التعديلات والتحققات المطلوبة في برمجياتك.
