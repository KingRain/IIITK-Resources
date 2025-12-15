# Handwritten Notes - Trees & Binary Trees
## Batch 2 - CS201

---

## Tree Terminology

```
        A           <- Root
       / \
      B   C         <- Internal Nodes
     /|   |\
    D E   F G       <- Leaf Nodes
```

- **Root**: Topmost node (A)
- **Leaf**: Node with no children (D, E, F, G)
- **Height**: Longest path from root to leaf
- **Depth**: Distance from root to a node

---

## Binary Tree Properties

1. Max nodes at level i = 2^i
2. Max nodes in tree of height h = 2^(h+1) - 1
3. Min height for n nodes = log₂(n+1) - 1

---

## Tree Traversals

### Inorder (Left, Root, Right)
```
D → B → E → A → F → C → G
```

### Preorder (Root, Left, Right)
```
A → B → D → E → C → F → G
```

### Postorder (Left, Right, Root)
```
D → E → B → F → G → C → A
```

---

*Handwritten notes transcribed - Batch 2*
