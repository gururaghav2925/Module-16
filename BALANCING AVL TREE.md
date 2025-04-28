# Experiment 10(b): Balancing AVL Tree

## Aim
To write a Python program to construct an AVL tree, balance it, and print the nodes of the tree before and after balancing using the appropriate packages and built-in functions.

---

## Algorithm

1. Start the program.
2. Define `getDictTree(self)` to return the dictionary representation of the AVL tree.
3. Define `Construct_AVL(L)` to:
   - Create the AVL tree from the list `L`.
   - Print the tree before balancing.
   - Balance the tree using the `BalanceTree()` method.
   - Print the tree after balancing.
4. Create a list `L` of integers.
5. Call `Construct_AVL(L)` to build and balance the tree.
6. End the program.

---

## Program

```python
from TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
  tree = AVL(L)
  print("AVL Tree Before Balancing\n",getDictTree(tree))
  tree.BalanceTree()
  print("AVL Tree After Balancing\n",getDictTree(tree))
L=[11,8,18,5,13,17,4,7,2]

```
## OUTPUT


![431419337-cd184680-75da-467a-9b59-90622933dea5](https://github.com/user-attachments/assets/201d1f24-64be-46ad-97a4-7fea34a771e4)

## RESULT
The program builds the binary search tree using the given elements and balances it using AVL rotations.
Both inorder traversals before and after balancing remain the same, confirming that the tree structure respects the binary search property, and balancing ensures minimal height.
