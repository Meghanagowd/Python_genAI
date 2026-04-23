 
# 🐍 Python Day 3 — Lists & Slicing

> Understanding collections in Python with focus on lists, operations, and slicing.

---

## 📚 Collections in Python

- List  
- Tuple  
- Dictionary  
- Set  

---

## 🔹 List Basics

- Lists can store **heterogeneous data types**

```python
data = [22, "hi", True, 5.6]

print(data[0])      # 22
print(data[1][1])   # i
````

❌ Invalid:

```python
print(data[2][0])   # Error (boolean is not indexable)
Error happens because **boolean is not subscriptable** 
```

---

## 📏 Length of List

```python
data = [22, "hi", True, 5.6]
print(len(data))   # 4
```

---

## ➕ Adding Elements

```python
data.append("hello")   # adds at end
```

---

## 🔧 List Methods

```python
names = ["shiva", "pree", "rama"]
```

### ✔ append()

```python
names.append("sita")
```

### ✔ insert(index, value)

```python
names.insert(1, "hanuman")
```

### ✔ remove(value)

```python
names.remove("pree")
```

### ✔ pop()

```python
names.pop()        # removes last
names.pop(1)       # removes element at index
```

### ✔ index()

```python
names.index("rama")   # returns index
```

### ✔ count()

```python
nums = [1,2,2,3]
nums.count(2)   # 2
```

### ✔ reverse()

```python
names.reverse()
```

### ✔ sort()

```python
nums = [3,1,2]
nums.sort()
```

---

## 🔄 List Creation

```python
s = "hanuman"
my_list = list(s)

nums = list([1,2,3])
```

---

## 🔍 Membership Operators

```python
s = "abc"

if 'b' in s:
    print("yes")

if 'x' not in s:
    print("no")
```

---

## 🔪 List Slicing

```python
nums = [10, 20, 30, 40, 50]
```

### ✔ Basic Slicing

```python
print(nums[1:4])   # [20, 30, 40]
print(nums[:3])    # [10, 20, 30]
print(nums[2:])    # [30, 40, 50]
```

### ✔ Step Slicing

```python
print(nums[0:4:2])   # [10, 30]
```

### ✔ Negative Indexing

```python
print(nums[-5:-2])   # [10, 20, 30]
```

### ✔ Reverse List

```python
print(nums[::-1])   # [50, 40, 30, 20, 10]
```

---

## 🔤 String Slicing

```python
s = "abc"

print(s[::-1])   # cba
print(s)         # abc
```

---

## 💡 Key Learnings

* Lists can store multiple data types
* Indexing depends on element type
* List methods simplify operations
* Slicing is powerful and flexible
* Reverse can be done in one line

---



 