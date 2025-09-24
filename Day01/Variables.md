# Variables

---

# What is a variable?

### In programming, a variable is a named storage location that holds a value or a piece of data.

### Simply put, a variable is a container used to store something.

---

### ✅ Rules for declaring variables with Examples

---

### 1. **Variable names can contain only letters, numbers, and underscores**

✔️ Valid:

```python
message1 = "Hello"
user_name = "Ravi"
total_amount2 = 500

```

❌ Invalid:

```python
user-name = "Ravi"   # ❌ dash not allowed
total$ = 100         # ❌ special characters not allowed

```

---

### 2. **A variable can start with a letter or an underscore, but not with a number**

✔️ Valid:

```python
message = "Hi"
_message = "Hello"
message_1 = "How are you?"

```

❌ Invalid:

```python
1_message = "Error"   # ❌ starts with number

```

---

### 3. **Spaces are not allowed in variable names. Use underscores instead**

✔️ Valid:

```python
greeting_message = "Good Morning"
user_age = 25

```

❌ Invalid:

```python
greeting message = "Hi"   # ❌ space not allowed

```

---

### 4. **Avoid using Python reserved keywords as variable names**

✔️ Valid:

```python
class_name = "Python"   # okay, because not just `class`
my_list = [1, 2, 3]

```

❌ Invalid (these are **reserved keywords**):

```python
class = "Python"   # ❌ error
for = 10           # ❌ error
if = "Hello"       # ❌ error

```

---

### 5. **Variable names are case-sensitive**

✔️ All are different variables:

```python
name = "ravi"
Name = "Ravi"
NAME = "RAVI"
print(name, Name, NAME)
# Output: ravi Ravi RAVI

```

---

### 6. **Variable names should be short but descriptive**

✔️ Good practice:

```python
age = 25
user_age = 25
file_count = 10

```

❌ Bad practice:

```python
x = 25        # not descriptive
asdf = 100    # meaningless

```

---

## **Python Comments**

- **Comments are helpful to document about the code, how it works, what is it’s importance and etc.**
- **Python interpreter ignores Comments during program execution.**

### Python has two types of Comments

### i)Single-line Comments

- **It start’s with # and used to comment line by line.**

### ii)Multi-line Comments

- **it start’s with tripule double quotes  “”” ”””  or  tripule single  quotes ‘’’ ‘’’  and used to comment a block of text or paragraph.**

**The shortcut-key to Comment any number of lines is Ctrl + /**