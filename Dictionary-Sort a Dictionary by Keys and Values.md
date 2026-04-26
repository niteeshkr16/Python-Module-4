# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
~~~
d = {'banana': 3, 'apple': 5, 'cherry': 1}

sorted_keys = dict(sorted(d.items()))
sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))

print("Original:", d)
print("Sorted by Keys:", sorted_keys)
print("Sorted by Values:", sorted_values)
~~~

## Sample Output
<img width="750" height="296" alt="image" src="https://github.com/user-attachments/assets/a8f1ea29-6d09-40bf-bcb1-fc96748b6845" />

## Result
Thus, The To write a Python program that sorts a dictionary according to its Keys in alphabetical order and to its Values in alphabetical order was executed successfully.
