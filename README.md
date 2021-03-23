# rtree
Rtree inspired by https://github.com/mourner/rbush. This RTree supports a number of alternative bulkloaders and optionally the use of recursion.

The RTree is generic. However, the type of the tree is defined not by the objects it contains, but the leaf nodes. This is so that non-rectangular leaf nodes can be used and the presence of data is optional.
