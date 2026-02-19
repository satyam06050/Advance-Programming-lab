| Q.No | Core Task                      | Most Important Function / Keyword      | 1-Line Explanation                                            |
| ---- | ------------------------------ | -------------------------------------- | ------------------------------------------------------------- |
| 1    | Matrix multiplication (NumPy)  | `np.dot()` or `@`                      | Performs optimized matrix multiplication using vectorization. |
| 1    | Time comparison                | `time.time()`                          | Measures execution time to compare performance.               |
| 2    | Create random array            | `np.random.randint()`                  | Generates random integer NumPy array of given shape.          |
| 2    | Conditional sum (odd/even)     | Boolean masking (`arr % 2`)            | Filters elements based on condition without loops.            |
| 2    | Diagonal sum                   | `np.trace()`                           | Computes sum of main diagonal elements.                       |
| 2    | Transpose                      | `.T`                                   | Swaps rows and columns of array.                              |
| 2    | Statistical measures           | `sum()`, `mean()`, `median()`, `std()` | Computes aggregate and dispersion values.                     |
| 2    | Flatten array                  | `flatten()` or `reshape(-1)`           | Converts 2D array into 1D array.                              |
| 3    | Reverse rows                   | `arr[::-1]`                            | Reverses order of rows.                                       |
| 3    | Reverse columns                | `arr[:, ::-1]`                         | Reverses elements within each row.                            |
| 3    | Remove border                  | `arr[1:-1, 1:-1]`                      | Removes first/last row and column.                            |
| 4    | Solve linear system            | `np.linalg.inv()` + `np.dot()`         | Uses inverse matrix method to solve equations.                |
| 4    | Direct solving (better method) | `np.linalg.solve()`                    | Efficiently solves linear equations without explicit inverse. |
| 5    | Create perimeter array         | `np.ones()` + slicing                  | Creates 1s on border and sets inside to 0.                    |
| 6    | Manual flatten                 | Nested loops                           | Converts 2D to 1D without NumPy built-ins.                    |
| 7    | Reverse rows in-place          | Slice assignment                       | `arr[:] = arr[::-1]` modifies array without creating new one. |
| 8    | Checkerboard pattern           | `np.indices()` or slicing step `::2`   | Creates alternating 0 and 1 pattern efficiently.              |
| 9    | 3D slicing                     | `arr[:, 1, :]`                         | Extracts middle row from each 2D layer.                       |
| 10   | Common elements                | `np.intersect1d()`                     | Finds common elements between two arrays without loops.       |
