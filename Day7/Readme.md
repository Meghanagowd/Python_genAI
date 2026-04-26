 
# 🐍 Day 7 – Python Learning

## 📌 Topics Covered
- List Comprehension
- Dictionary Comprehension
- Try & Except (Error Handling)

---

# 🧠 LIST COMPREHENSION

### 🔹 Definition
A shorter way to create lists using a single line of code.

---

### 🔹 Basic Syntax

```python
[expression for item in iterable]
````

---

### 🔹 Example

```python
nums = [1, 2, 3, 4]

squares = [n * n for n in nums]
print(squares)
# [1, 4, 9, 16]
```

---

### 🔹 With Condition

```python id="7l4s0f"
nums = [1, 2, 3, 4, 5]

evens = [n for n in nums if n % 2 == 0]
print(evens)
```

---

### 🔹 If-Else in List

```python id="k3p9zm"
nums = [1, 2, 3]

result = ["even" if n % 2 == 0 else "odd" for n in nums]
print(result)
```

---

# 🧠 DICTIONARY COMPREHENSION

### 🔹 Syntax

```python
{key: value for item in iterable}
```

---

### 🔹 Example

```python id="3m2h8a"
result = {x: x * x for x in range(5)}
print(result)
# {0:0, 1:1, 2:4, 3:9, 4:16}
```

---

### 🔹 With Condition

```python id="r9v2kx"
nums = [1, 2, 3, 4]

result = {x: ("even" if x % 2 == 0 else "odd") for x in nums}
print(result)
```

---

# 🧠 TRY & EXCEPT (Error Handling)

### 🔹 Purpose

Used to handle errors and prevent program crash.

---

### 🔹 Basic Syntax

```python id="p8u3ln"
try:
    # risky code
except:
    # handle error
```

---

### 🔹 Example (Division)

```python id="d4t7bs"
try:
    n = int(input("Enter number: "))
    print(10 / n)
except ZeroDivisionError:
    print("Cannot divide by zero")
```

---

### 🔹 Handling Multiple Errors

```python id="j5x1rt"
try:
    n = int(input())
    print(10 / n)
except ZeroDivisionError:
    print("Divide by zero error")
except ValueError:
    print("Invalid input")
```

---

### 🔹 Full Structure

```python id="n2b6kq"
try:
    n = int(input())
    print(10 / n)
except:
    print("Error occurred")
else:
    print("Success")
finally:
    print("Done")
```

---

# 🚀 IMPORTANT PROGRAMS

---

## 🔹 Squares using comprehension

```python id="a1c9zq"
nums = [1, 2, 3, 4]
print([n * n for n in nums])
```

---

## 🔹 Filter even numbers

```python id="u3r8dp"
nums = [1, 2, 3, 4]
print([n for n in nums if n % 2 == 0])
```

---

## 🔹 Flatten 2D list

```python id="q8z4ty"
matrix = [[1, 2], [3, 4]]

flat = [item for row in matrix for item in row]
print(flat)
```

---

## 🔹 Remove duplicates

```python id="x6p2we"
nums = [1, 2, 2, 3]

print(list(set(nums)))
```

---

# ⚠️ COMMON MISTAKES

* ❌ Wrong syntax in comprehension
* ❌ Forgetting `else` in inline condition
* ❌ Using try without except
* ❌ Catching all errors blindly

---

# 💡 KEY POINTS

* List comprehension = cleaner loops
* Dictionary comprehension = mapping data
* Try/Except = safe execution
* Helps write concise and readable code

---
 