# List Matrix Edges

In programming, we can create a matrix of arrays by nesting arrays within arrays. A two dimensional example of this is:

```
[[1, 2, 3, 4, 5],
[6, 7, 8, 9, 10],
[11, 12, 13, 14, 15],
[16, 17, 18, 19, 20],
[21, 22, 23, 24, 25]]
```

Each nested array is a "row" in the matrix.

Given a two dimensional matrix-like array similar to the one above, build a method / function that returns an array of all the "outer" values that are on the "edge" of the array.

```
const matrix = [
  [1,2,3],
  [4,5,6],
  [7,8,9]
]

getEdges(matrix) --> [1,2,3,6,9,8,7,4]
```

```
const matrix = [
  [1,2],
  [3,4]
]

getEdges(matrix) --> [1,2,4,3]
```

```
const matrix = [
  [1, 2, 3, 4, 5],
  [6, 7, 8, 9, 10],
  [11, 12, 13, 14, 15],
  [16, 17, 18, 19, 20],
  [21, 22, 23, 24, 25]
]

getEdges(matrix) --> [1,2,3,4,5,10,15,20,25,24,23,22,21,16,11,6]
```

The edge values can be returned in whatever order you like.
