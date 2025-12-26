# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1=[5, 10, 20] 
try: 
   print(list1[5]) 
except: 
   print("You're out of list range")
```
## Output
<img width="913" height="207" alt="image" src="https://github.com/user-attachments/assets/a1570bb0-f2ee-4c76-ab77-78e40881b72e" />


## Result
Thus,the python program to handle an IndexError when trying to access an element beyond the available range of a list is executed successfully.
