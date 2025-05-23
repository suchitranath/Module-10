# EX.NO:10(A) Queue-Queue Values in Descending Order Using Python 

This Python program simulates a queue using a list, removes the first two elements (FIFO order), and displays the remaining values in descending order.

## Aim

To write a Python program to:
- Accept user inputs into a list (queue)
- Remove the first two elements (simulating dequeue)
- Display the remaining values in **descending order**

## Algorithm

1. Create an empty list `q`.
2. Read an integer `n` to determine how many elements will be added.
3. Loop `n` times:
   - Read an input value.
   - Append it to the list `q`.
4. Remove the first element using `pop(0)`.
5. Remove the second element using `pop(0)` again.
6. Sort the list in descending order.
7. Print the updated list.

## Program: 
```
from queue import PriorityQueue 

que = PriorityQueue() 
n = int(input("Enter number of elements: ")) 
l = [] 

for i in range(n): 
    l.append(int(input()))
for number in l: 
    que.put((-number, number)) 
print("Elements in descending order:")
while not que.empty(): 
    print(que.get()[1])

```
### Output:
![image](https://github.com/user-attachments/assets/23ee2114-8645-4393-8730-9e76661d1e18)

## Result:
Thus the program has been successfully executed
