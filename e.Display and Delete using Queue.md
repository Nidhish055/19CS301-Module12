# 12 e. Display and Delete using Queue

## Aim

To write a Python program display all the elements inserted and also display after deleting the first element.

## Algorithm

1. Initialize empty list as queue
2. Use append() to insert elements at the end
3. Use pop(0) to remove the first (front) element (FIFO)
4. Print queue after each operation

## Program

```python
# Name: Nidhish B
# Reg.No: 212223050032

queue = []

queue.append('a')
queue.append('b')
queue.append('c')
queue.append('d')

print('Initial Queue: ' + str(queue))

front=queue[0]

print("\nElement at the front of the queue is .... ",front)

rear=queue[3]

print("\nElement at the rear of the queue is .... ",rear)

```
## OUTPUT

![image](https://github.com/user-attachments/assets/fa8b0abc-7e25-4d39-9bef-8d1de8a88a17)


## RESULT

Thus,the given program is implemented and executed successfully.
