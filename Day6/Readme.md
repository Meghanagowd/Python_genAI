  
# 🐍 Day 6 – Python Learning

## 📌 Topics Covered
- Functions
- Arguments (Positional, Keyword, Default)
- Return Statement
- *args and **kwargs
- Local vs Global Variables
- Lambda Function

---

# 🧠 FUNCTIONS

### 🔹 Definition
A function is a reusable block of code used to perform a specific task.

---

### 🔹 Syntax

```python
def function_name():
    print("Hello")

function_name()
````

---

# 🔹 PARAMETERS & ARGUMENTS

---

## ✅ 1. Positional Arguments

```python id="1p8k7v"
def add(a, b):
    print(a + b)

add(5, 6)
```

---

## ✅ 2. Keyword Arguments

```python id="9j3dsa"
def func(a, b):
    print(a)

func(b=5, a=6)
```

---

## ✅ 3. Default Arguments

```python id="h9sk2x"
def greet(name="Meghana"):
    print(name)

greet()          # Meghana
greet("Mango")   # Mango
```

---

# 🔹 RETURN STATEMENT

* Used to send value back from function

```python id="v3l0mz"
def fun():
    return 5

x = fun()
print(x)
```

---

# 🔹 *ARGS (Multiple Arguments)

```python id="7mq3rl"
def fun(*numbers):
    print(numbers)

fun(1, 2, 3)   # (1, 2, 3)
```

---

# 🔹 **KWARGS (Key-Value Arguments)

```python id="4s8nbp"
def fun(**data):
    print(data)

fun(name="Meghana", age=20)
```

---

# 🔹 MIXED ARGUMENTS

```python id="n8w2tp"
def fun(a, b, *c):
    print(c)

fun(1, 2, 3, 4, 5)   # (3, 4, 5)
```

---

# 🔹 LOCAL & GLOBAL VARIABLES

---

## ✅ Local Variable

```python id="o3h1df"
def fun():
    x = 10
    print(x)

# print(x) ❌ Error
```

---

## ✅ Global Variable

```python id="s7k9qw"
x = 10

def fun():
    print(x)

fun()
```

---

## ✅ Global Keyword

```python id="k1z8po"
x = 10

def fun():
    global x
    x = 20

fun()
print(x)   # 20
```

---

# 🔹 LAMBDA FUNCTION

* One-line function

```python id="y7g3nv"
sum = lambda a, b: a + b

print(sum(5, 6))
```

---

# 🚀 IMPORTANT PROGRAMS

---

## 🔹 Add Function

```python id="c9l8we"
def add(a, b):
    return a + b
```

---

## 🔹 Factorial

```python id="x2m7kd"
def fact(n):
    f = 1
    for i in range(1, n + 1):
        f *= i
    return f
```

---

## 🔹 Reverse String

```python id="j3v8lp"
def reverse(s):
    rev = ""
    for ch in s:
        rev = ch + rev
    return rev
```

---

## 🔹 Palindrome Check

```python id="r8u2bn"
def is_palindrome(s):
    return s == reverse(s)
```

---

# ⚠️ COMMON MISTAKES

* ❌ Forgetting `return`
* ❌ Using variable outside function (scope issue)
* ❌ Confusing *args and **kwargs
* ❌ Wrong indentation

---

# 💡 KEY POINTS

* Functions make code reusable
* `return` is important
* *args → multiple values
* **kwargs → key-value pairs
* Scope matters (local vs global)

---
 