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
~~~
my_list = [10, 20, 30, 40, 50]
try:
    index = int(input("Enter the index to access (0 to 4): "))
    print(f"Element at index {index}: {my_list[index]}")
except IndexError:
    print("⚠️ IndexError: That index is out of range.")
except ValueError:
    print("⚠️ ValueError: Please enter a valid integer.")
~~~

## Output
<img width="472" height="134" alt="image" src="https://github.com/user-attachments/assets/0c417134-217a-4dea-ad16-1b0622f5572c" />

## Result
Thus , the program has been executed successfully.
