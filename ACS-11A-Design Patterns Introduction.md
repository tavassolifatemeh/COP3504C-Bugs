# Slide Number: 8

## Description
The virtual Renderer destructor is missing parenthesis, could cause a compilation error.

## Possible Fix
Change from (virtual  ~Renderer {}) to (virtual ~Renderer () {} ) 

## Name: Lokaghna Velugu Boreddi
