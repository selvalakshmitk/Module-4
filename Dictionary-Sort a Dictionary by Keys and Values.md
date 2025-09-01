# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
from collections import OrderedDict

d={'ravi':'10','rajnish':'9','sanjeev':'15','yash':'2','suraj':'32'}

d1=OrderedDict(sorted(d.items()))

print(d1)

## Sample Output
<img width="1225" height="165" alt="image" src="https://github.com/user-attachments/assets/ff1e8ce7-4b94-4191-b831-c81cf38d3a04" />


## Result
Thus, Python program that sorts a dictionary's Keys in alphabetical order is excuted and verified.
