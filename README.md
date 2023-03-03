# 0x1D. C - Binary trees

In this project, I learned about the details, advantages, and disadvantages of using trees as data structures. I learned about how to
qualify trees as well as how to traverse them. Throughout the project, I implemented binary, binary search, AVL, and Max Binary Heap trees.

# Function Prototypes

| File                             | Prototype                                                                                             |
| -------------------------------- | ----------------------------------------------------------------------------------------------------- |
| `binary_trees.h`                 | Header file containing definitions and prototypes for all types and functions written for the project |
| `binary_tree_print.c`            | `void binary_tree_print(const binary_tree_t *tree)`                                                   |
| `0-binary_tree_node.c`           | `binary_tree_t *binary_tree_node(binary_tree_t *parent, int value);`                                  |
| `1-binary_tree_insert_left.c`    | `binary_tree_t *binary_tree_insert_left(binary_tree_t *parent, int value);`                           |
| `2-binary_tree_insert_right.c`   | `binary_tree_t *binary_tree_insert_right(binary_tree_t *parent, int value);`                          |
| `3-binary_tree_delete.c`         | `void binary_tree_delete(binary_tree_t *tree);`                                                       |
| `4-binary_tree_is_leaf.c`        | `int binary_tree_is_leaf(const binary_tree_t *node);`                                                 |
| `5-binary_tree_is_root.c`        | `int binary_tree_is_root(const binary_tree_t *node);`                                                 |
| `6-binary_tree_preorder.c`       | `void binary_tree_preorder(const binary_tree_t *tree, void (*func)(int));`                            |
| `7-binary_tree_inorder.c`        | `void binary_tree_inorder(const binary_tree_t *tree, void (*func)(int));`                             |
| `8-binary_tree_postorder.c`      | `void binary_tree_postorder(const binary_tree_t *tree, void (*func)(int));`                           |
| `9-binary_tree_height.c`         | `size_t binary_tree_height(const binary_tree_t *tree);`                                               |
| `10-binary_tree_depth.c`         | `size_t binary_tree_depth(const binary_tree_t *tree);`                                                |
| `11-binary_tree_size.c`          | `size_t binary_tree_size(const binary_tree_t *tree);`                                                 |
| `12-binary_tree_leaves.c`        | `size_t binary_tree_leaves(const binary_tree_t *tree);`                                               |
| `13-binary_tree_nodes.c`         | `size_t binary_tree_nodes(const binary_tree_t *tree);`                                                | 
| `14-binary_tree_balance.c`       | `int binary_tree_balance(const binary_tree_t *tree);`                                                 |
| `15-binary_tree_is_full.c`       | `int binary_tree_is_full(const binary_tree_t *tree);`                                                 |
| `16-binary_tree_is_perfect.c`    | `int binary_tree_is_perfect(const binary_tree_t *tree);`                                              |
| `17-binary_tree_sibling.c`       | `binary_tree_t *binary_tree_sibling(binary_tree_t *node);`                                            |
| `18-binary_tree_uncle.c`         | `binary_tree_t *binary_tree_uncle(binary_tree_t *node);`                                              |
