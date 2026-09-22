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
```
d = {'banana': 3, 'apple': 1, 'cherry': 2}

print("Original dictionary:", d)

sorted_keys = dict(sorted(d.items()))
print("Sorted by keys:", sorted_keys)

sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))
print("Sorted by values:", sorted_values)
```

## Sample Output
<img width="1306" height="242" alt="image" src="https://github.com/user-attachments/assets/5ab2e5ab-ed72-4714-b57d-e2f8db089264" />


## Result

