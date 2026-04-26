

 

````markdown
# 🐍 Day 4 – Python (Revision Notes)

## 📌 Topics
- String Functions
- String Operations
- Loops (for, while)
- Practice Problems

---

# 🧠 STRING FUNCTIONS (Quick Revision)

| Function | Description | Example |
|--------|------------|--------|
| `upper()` | Convert to uppercase | `"hi".upper()` → `HI` |
| `lower()` | Convert to lowercase | `"HI".lower()` → `hi` |
| `title()` | Capitalize each word | `"hello world"` → `Hello World` |
| `capitalize()` | Capitalize first letter | `"hello"` → `Hello` |

---

# 🔍 SEARCH FUNCTIONS

| Function | Behavior |
|--------|---------|
| `find()` | Returns index OR `-1` |
| `index()` | Returns index OR **error** |

```python
text = "abcd"
print(text.find("bcd"))   # 1
print(text.index("bcd"))  # 1
````

---

# 🔢 COUNT & REPLACE

```python
text = "aabcad"
print(text.count("a"))   # 3

text = "hello world"
print(text.replace("world", "python"))
```

---

# ✂️ STRIP FUNCTIONS

```python
text = "   hello   "

text.strip()   # remove both sides
text.lstrip()  # left side
text.rstrip()  # right side
```

---

# 🔗 SPLIT & JOIN

```python
text = "hello world"
text.split()   # ['hello', 'world']

text = "a.b.c"
text.split(".")  # ['a', 'b', 'c']

words = ["hello", "world"]
" ".join(words)   # hello world
```

---

# ✅ CHECK FUNCTIONS

```python
text = "abc"

text.isalpha()   # True
text.isdigit()   # False
text.isalnum()   # True
```

> ⚠️ No `++` or `--` in Python

---

# 🔁 LOOPS

---

## 🔄 FOR LOOP

```python
for i in range(1, 11):
    print(i)

for i in range(5):
    print(i)

for i in range(1, 10, 2):
    print(i)
```

---

## 📊 TABLE PROGRAM

```python
n = int(input())

for i in range(1, 11):
    print(n * i)
```

---

## 🔤 LOOPING STRING

```python
text = "abc"

for ch in text:
    print(ch)

# Using index
for i in range(len(text)):
    print(text[i])
```

---

## 📋 LOOPING LIST

```python
my_list = [1, 2, 3]

for i in my_list:
    print(i)
```

---

## 🔎 FIND INDEX OF 'a'

```python
s = "abcdefaab"

for i in range(len(s)):
    if s[i] == 'a':
        print(i)
```

---

## 🔢 COUNT OCCURRENCES

```python
s = "ababac"

count = 0
for ch in s:
    if ch == 'a':
        count += 1

print(count)
```

---

## 📥 USER INPUT LIST

```python
my_list = []

for i in range(5):
    my_list.append(input())
```

---

## 🔲 2D LIST

```python
matrix = [[1,2,3],[4,5],[6]]

for row in matrix:
    for val in row:
        print(val)
```

---

# 🔁 WHILE LOOP

```python
i = 1

while i < 10:
    print(i)
    i += 1
```

---

# 🧮 IMPORTANT PROGRAMS

## 🔹 Sum of Digits

```python
n = 1234

total = 0
for digit in str(n):
    total += int(digit)

print(total)
```

---

## 🔹 Reverse Number

```python
n = 123
print(str(n)[::-1])
```

---
 
 
 