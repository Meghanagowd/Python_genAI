
# 🐍 Python Day 2 — Input, Operators & Conditions

> Building on basics by understanding input handling, operators, and decision-making in Python.

---

## 🖨️ Print Methods

```python
name = "Meghana"
marks = 98
````

### ✔ Concatenation

```python
print("My name is " + name + " and my marks is " + str(marks))
```

### ✔ Comma-Separated

```python
print("My name is", name, "and my marks is", marks)
```

### ✔ f-String (Best)

```python
print(f"My name is {name} and my marks is {marks}")
```

---

## ⌨️ User Input

```python
n = input("Enter a number: ")
print(n)
print(type(n))   # Always string
```

---

### ⚠️ Important Case

```python
a = input()
b = input()

print(a + b)   # Concatenation
```

✔ Correct:

```python
print(int(a) + int(b))
```

---

## ➗ Arithmetic Operators

```python
a = 3
b = 2

print(a + b)   # 5
print(a - b)   # 1
print(a * b)   # 6
print(a / b)   # 1.5
print(a % b)   # 1
```

---

### 🔹 Floor Division

```python
print(3 // 2)   # 1
```

---

## 🔍 Relational Operators

```python
a = 5
b = 6

print(a > b)
print(a < b)
print(a >= b)
print(a <= b)
print(a == b)
print(a != b)
```

✔ Output: True / False

---

## 🔗 Logical Operators

```python
print(True and False)
print(True or False)
print(not True)
```

---

## ⚙️ Decision Making (if-else)

```python
a = 5

if a >= 5:
    print("hi")
    print("hello")

print("end")
```

---

## 📌 Nested if

```python
a = 5
b = 6

if a == 5:
    print("a")
    if b == 6:
        print("b")
    else:
        print("c")
else:
    print("d")
```

---

## ⚠️ Indentation (Important)

```python
a = 5

if a > 5:
    print("hi")
    print("hello")   # Must align properly
```

❌ Incorrect indentation → Error

---

## 🔄 if-else Example

```python
a = 5

if a == 5:
    print("hello")
else:
    print("hi")
```

---

## 🔁 elif Example

```python
marks = 68

if marks >= 90:
    print("A")
elif marks >= 75:
    print("B")
elif marks >= 50:
    print("C")
else:
    print("Fail")
```

---

## 💡 Key Learnings

* `input()` always returns string
* Type conversion is necessary for calculations
* f-strings provide clean formatting
* Indentation defines code blocks in Python
* Conditions control program flow

---
 

---

  
