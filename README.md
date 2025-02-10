# Off-by-One Error in C++ Vector Iteration
This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`. The error occurs because the loop condition `i <= vec.size()` attempts to access an element beyond the valid range of the vector.  Vectors are zero-indexed, so the last valid index is `vec.size() - 1`.

The `bug.cpp` file contains the erroneous code, while `bugSolution.cpp` provides the corrected version.  This example highlights the importance of careful attention to loop bounds when working with vectors and other dynamic data structures in C++.