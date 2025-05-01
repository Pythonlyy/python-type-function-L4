# 🔍 Using `type()` to Check Data Types in Python

The `type()` function in Python shows you what kind of data a value or variable holds.
It’s useful for debugging, learning, and writing better code.

Use it with:
- Strings
- Integers
- Floats
- Booleans

---

## 💻 Example with Explanation

```python
name = "Alice"
age = 30
height = 1.65
is_coding = True

print(type(name))      # str
print(type(age))       # int
print(type(height))    # float
print(type(is_coding)) # bool
```

### 🔈 Output

```
<class 'str'>
<class 'int'>
<class 'float'>
<class 'bool'>
```

---

### 📌 Key Notes

- `type()` returns the class name of the data type
- It's often used for:
  - Debugging
  - Learning what kind of data you're working with
  - Verifying user input
- Works on variables **or** raw values:
  ```python
  print(type(3.14))
  print(type("hello"))
  ```

---

## 🧪 Try It Yourself

```python
value1 = 100
value2 = "100"

print("value1 is:", type(value1))
print("value2 is:", type(value2))
```

### 🔈 Expected Output

```
value1 is: <class 'int'>
value2 is: <class 'str'>
```

---

🐍 This is part of the **Pythonly** beginner series.  
Learn Python one line at a time. Follow **@Pythonly** for more.

---


