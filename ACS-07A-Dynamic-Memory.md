# Slide Number: 4
## Description
The slide includes an example float scores[input]; which uses a variable-length array, a feature not supported in standard C++. This might lead students to believe it's a valid C++ practice, which could result in compilation errors in non-GNU compilers.

## Possible Fix
Clarify that variable-length arrays are not standard in C++ and show proper dynamic memory allocation using new, such as float* scores = new float[input];. Explain the standard-compliant alternatives for dynamic array handling, such as using std::vector.

## Name: Jennifer Senra Bruzon

# Slide Number: 10
## Description
The explanation of dynamic memory management with new and delete lacks a detailed discussion on the importance of avoiding memory leaks and the necessity of using delete[] for arrays allocated with new[]. This omission could lead to poor coding practices.

## Possible Fix
Expand the slide to include examples of common mistakes in dynamic memory management, such as memory leaks and mismatched new[]/delete. Explain the consequences of these errors and how to properly manage memory in C++ to prevent such issues.

## Name: Jennifer Senra Bruzon
