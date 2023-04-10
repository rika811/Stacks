# Stacks

## What is Stack?

A stack is a linear data structure in which the insertion of a new element and removal of an existing element takes place at the same end represented as the top of the stack.

To implement the stack, it is required to maintain the pointer to the top of the stack, which is the last element to be inserted because we can access the elements only on the top of the stack.

### LIFO( Last In First Out ):

This strategy states that the element that is inserted last will come out first. You can take a pile of plates kept on top of each other as a real-life example. The plate which we put last is on the top and since we remove the plate that is at the top, we can say that the plate that was put last comes out first.

### Basic Operations on Stack

In order to make manipulations in a stack, there are certain operations provided to us.

+ push() to insert an element into the stack
+ pop() to remove an element from the stack
+ top() Returns the top element of the stack.
+ isEmpty() returns true if stack is empty else false.
+ size() returns the size of stack.

### Push:
Adds an item to the stack. If the stack is full, then it is said to be an Overflow condition.

#### Algorithm for push:

```
begin
 if stack is full
    return	
 endif
else 
 increment top
 stack[top] assign value
end else
end procedure
```

### Pop:
Removes an item from the stack. The items are popped in the reversed order in which they are pushed. If the stack is empty, then it is said to be an Underflow condition.

#### Algorithm for pop:

```
begin
 if stack is empty
    return	
 endif
else
 store value of stack[top]
 decrement top
 return value
end else
end procedure
```

### Top:
Returns the top element of the stack.

#### Algorithm for Top:

```
begin 
  return stack[top]	
end procedure
```

### isEmpty:
Returns true if the stack is empty, else false.

#### Algorithm for isEmpty:

```
begin
 if top < 1
    return true	
 else
    return false		
end procedure
```
Output-

![Screenshot 2023-04-10 at 4 57 43 PM](https://user-images.githubusercontent.com/91966167/230893227-cbc07d70-f183-4068-84a1-9005e3082150.png)

