 
# 🐍 Day 5 – Python Learning

## 📌 Topics Covered
- Dictionary
- Tuple
- Set
- Basic Operations

---

# 🧠 DICTIONARY

### 🔹 Definition
- Stores data in **key-value pairs**
- Mutable (can be changed)
- No indexing (access using keys)

---

### 🔹 Creating Dictionary

```python
d = {}

d['a'] = 1
d['b'] = 2
d['c'] = 3

print(d)  
# {'a': 1, 'b': 2, 'c': 3}
````

---

### 🔹 Updating Values

```python
d['a'] = 5   # updates existing key
```

---

### 🔹 Accessing Values

```python
print(d['b'])   # 2
```

⚠️ Invalid:

```python
print(d[0])   # ❌ error (no indexing in dictionary)
```

---

### 🔹 Length of Dictionary

```python
print(len(d))
```

---

### 🔹 Traversing Dictionary

```python
for key in d:
    print(key, d[key])
```

---

# 🔥 FREQUENCY COUNT (Important Pattern)

```python
s = "ababca"

d = {}

for ch in s:
    if ch not in d:
        d[ch] = 1
    else:
        d[ch] += 1

print(d)
```

---

# 🧠 TUPLE

### 🔹 Definition

* Ordered collection
* Immutable (cannot be changed)

```python
t = (1, 2, 3)
```

---

# 🧠 SET

### 🔹 Definition

* Unordered collection
* No duplicate elements
* Mutable

```python
s = {1, 2, 2, 3}
print(s)   # {1, 2, 3}
```

---

### 🔹 Set Operations

| Operation            | Symbol |   |
| -------------------- | ------ | - |
| Union                | `      | ` |
| Intersection         | `&`    |   |
| Difference           | `-`    |   |
| Symmetric Difference | `^`    |   |

---

### 🔹 Example

```python
a = {1,2,3}
b = {2,3,4}

print(a | b)   # union
print(a & b)   # intersection
print(a - b)   # difference
print(a ^ b)   # symmetric difference
```

---

### 🔹 Remove Duplicates Using Set

```python
s = "abcaabdea"

unique = set(s)
print(len(unique))
```

---

# ⚠️ COMMON MISTAKES

* ❌ Using index in dictionary → `d[0]`
* ❌ Forgetting key existence check
* ❌ Assuming set maintains order
* ❌ Duplicate keys overwrite values

---

# 💡 KEY POINTS

* Dictionary → key-value storage
* Tuple → immutable data
* Set → unique elements
* Frequency logic is important

---

 
```
