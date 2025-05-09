# 12 c Queue Using Linked List – Display, Peek, and Pop

## Aim

To write a Python program to Insert 5 elements in a queue and delete some specific elements from queue and display how many elements remains in the queue. 

## Algorithm

1. Start  
2. Initialize empty queue  
3. Add elements 
4. Show queue  
5. Remove elements at index
6. Show updated queue  
7. End

## Program

```python
# Name: Nidhish B
# Reg.No: 212223050032

queue = []

queue.append('a')
queue.append('b')
queue.append('c')
queue.append('d')
queue.append('e')

print('Initial queue')
print(queue)

print("\nElements popped from queue:")
print(queue.pop(1))
print(queue.pop(3))

print('\nQueue after elements are popped:')
print(queue)
```

## OUTPUT

![Screenshot 2025-05-07 232507](https://github.com/user-attachments/assets/fd07a6a4-cdd9-4ddf-8dd8-ac923b402ec9)

## RESULT

Thus,the given program is implemented and executed successfully.
