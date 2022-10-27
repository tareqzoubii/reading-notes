## Read 12

## What is stack?

#### A stack is a linear data structure that follows the principle of Last In First Out (LIFO). This means the last element inserted inside the stack is removed first.

# -----------

## what is the operations that allow us to perform different actions on a stack?

#### *Push*: Add an element to the top of a stack
#### *Pop*: Remove an element from the top of a stack
#### *IsEmpty*: Check if the stack is empty
#### *IsFull*: Check if the stack is full
#### *Peek*: Get the value of the top element without removing it

# ----------

## How to implement stack with python?

> # Stack implementation in python
  # Creating a stack
  def create_stack():
    stack = []
    return stack
  # Creating an empty stack
  def check_empty(stack):
    return len(stack) == 0
  # Adding items into the stack
  def push(stack, item):
    stack.append(item)
    print("pushed item: " + item)
  # Removing an element from the stack
  def pop(stack):
    if (check_empty(stack)):
        return "stack is empty"

    return stack.pop()

# -----------

## What is meant by Top of the Stack?

#### The pointer through which the elements are accessed, inserted, and deleted in the stack is called the top of the stack. It is the pointer to the topmost element of the stack.