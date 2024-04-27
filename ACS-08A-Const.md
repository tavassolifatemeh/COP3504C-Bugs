# Slide Number: 1

## Description
The slide attempts to show an assignment to a const variable (pi = 12.4f;), which should generate a compiler error. However, the intent to demonstrate an error is not clearly communicated, which might confuse students about the functionality of const.

## Possible Fix
Clarify that this line is meant to show incorrect usage and is expected to produce a compiler error. It may help to add a note or comment in the slide stating this explicitly to prevent misunderstandings.

## Name: Jennifer Senra Bruzon

# Slide Number: 4

## Description
The explanation of pointers and const is confusing, especially regarding the const placement (const int* pointer vs. int* const pointer). The examples provided do not sufficiently differentiate between a pointer to const and a const pointer, which are fundamentally different concepts.

## Possible Fix
Provide clearer, separate examples for each case:

const int* pointer: Explain that the integer pointed to by pointer cannot be changed through this pointer.
int* const pointer: Explain that the pointer itself cannot point to another address, but the integer it points to can be modified.
Include diagrams or additional visual aids to illustrate these differences more effectively.

## Name: Michelle Garcia