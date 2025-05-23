#  EX.No:10(D)  Stack-Stack Reversal Program 

This Python program demonstrates how to reverse the values in a stack using basic stack operations like push and pop.

##  Aim

To write a Python program that reverses the values in a stack using standard stack operations.

##  Algorithm

1. Create an empty stack.
2. Read an integer `n` from the user (number of elements to push).
3. Loop `n` times:
   - Read an integer from the user.
   - Push it onto the stack.
4. Create an empty list called `reverse`.
5. While the stack is not empty:
   - Pop the top element.
   - Append it to `reverse`.
6. Print the reversed list.


### Program:
```
stack = [] 
n = int(input("Enter number of elements: ")) 

# Push elements onto the stack
for i in range(n): 
    value = int(input()) 
    stack.append(value) 

# Reverse the stack by popping
reverse = [] 
while stack: 
    reverse.append(stack.pop()) 

# Print the reversed list
print("Reversed Stack:", reverse)

```

## Output
![image](https://github.com/user-attachments/assets/2c75ff2d-c112-46a0-9d8a-a0fb0e9dc2be)

## Result
Thus the program has been successfully executed 
