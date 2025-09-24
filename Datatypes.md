# Datatypes

---

# Python Built-in Data Types (Basics)

## What is a Datatype ?

**A Datatype defines the type of a Data or Value, a Variable can hold and what Operations can be Performed on it.**

### 1. `int` → Integer

- Whole numbers (positive, negative, zero).
- No decimal part.
- Example:
    
    ```python
    x = 10
    y = -5
    z = 0
    ```
    

---

### 2. `float` → Floating-point Number

- Numbers with decimal part.
- Can also represent scientific notation.
- Example:
    
    ```python
    pi = 3.14
    temp = -12.5
    sci = 1.5e3   # 1500.0
    
    ```
    

---

### 3. `bool` → Boolean

- Represents truth values → `True` or `False`.
- Often result of comparisons.
- Example:
    
    ```python
    is_sunny = True
    print(5 > 3)   # True
    print(10 == 7) # False
    
    ```
    

---

### 4. `str` → String

- Sequence of characters enclosed in quotes (`' '` or `" "`).
- Immutable (cannot be changed in place).
- Example:
    
    ```python
    name = "Ravi"
    greet = 'Hello'
    multi = """This is
    multi-line string"""
    
    ```
    

---

### 5. `None` → Null / No Value

- Represents absence of a value.
- Often used as a placeholder or default return.
- Example:
    
    ```python
    x = None
    print(x)       # None
    print(type(x)) # <class 'NoneType'>
    
    ```
    

---