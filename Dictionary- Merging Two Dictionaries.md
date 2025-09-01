![WhatsApp Image 2025-09-01 at 15 52 10_8b52a655](https://github.com/user-attachments/assets/5ecc07c0-4fe2-41d9-aa74-60d17f8ffb62)## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}

dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}

dict3 = {*dict1,*dict2}

print(dict3)

## Output
![WhatsApp Image 2025-09-01 at 15 52 10_8b52a655](https://github.com/user-attachments/assets/b751d6a2-296a-4e09-bb5c-4e2796cd5505)


## Result
Thus, Python program that merges **two dictionaries** and combines their key-value pairs is excuted verified.
