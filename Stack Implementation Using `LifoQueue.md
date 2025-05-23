# EX.NO:10(C) Stack Implementation Using `LifoQueue` (Max Size 7) 

This Python program demonstrates a stack implemented using the `LifoQueue` class from the `queue` module. It allows up to 7 elements, checks if the stack is full, and then prints the elements in reverse (LIFO) order.

## Aim

To create a Python program that:
- Implements a stack using `LifoQueue` with a maximum size of 7
- Adds user-inputted values to the stack
- Checks whether the stack is full
- Prints the stack elements in reverse order (LIFO)

## Algorithm

1. Import the `LifoQueue` class from the `queue` module.
2. Create a stack with a maximum size of 7.
3. Read the number of elements (`n`) to be added to the stack.
4. Loop `n` times:
   - Read a value from the user.
   - Use `put()` to push it onto the stack if it's not full.
5. Use `full()` to check if the stack is full and print the result.
6. Use `get()` repeatedly to pop and print elements in reverse order.

## Program
```
q = [] 
n=int(input()) 
for i in range(n): 
    q.append(input()) 
q.pop(0) 
q.pop(0) 
print(q)
```

## Output
![image](https://github.com/user-attachments/assets/752acd18-ea53-4ca1-b72a-0b03b840e8e3)

## Result:
Thus the program has been successfully executed
