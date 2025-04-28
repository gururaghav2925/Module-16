# Experiment 10(a): AVL Tree

## Aim
To write a Python program to construct an AVL tree and print the nodes of it using the appropriate packages and built-in functions.

---

## Algorithm

1. Start the program.
2. Define a function `getDictTree(tree)` to return the dictionary representation of an AVL tree.
3. Define a function `Construct_AVL(L)` to:
   - Create an AVL tree from the list `L`.
   - Get and print the dictionary tree using `getDictTree(tree)`.
4. Define a list `L` with integer values.
5. Call `Construct_AVL(L)` to build the tree and print the result.
6. End the program.

---

## Program

```python
from TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
  tree = AVL(L)
  print(getDictTree(tree))

L=[12,8,18,5,11,17,4,7,2]

```

## OUTPUT

![431414746-13351379-cd7d-4e35-bd03-3d31f873963e](https://github.com/user-attachments/assets/3fa0296d-d839-416c-b858-b4ad2c298d25)

## RESULT
Thus The program inserts the values into an AVL tree while maintaining balance and prints it completed successfully.
