# Slide Number: 6

## Description
The call to the self._par attribute in the end of the __next__ function declaration is incorrect. The code shown uses self._parent._step but parent is a parameter and not accessible by this code.

## Possible Fix
The code should use self._par. 
self._pos += self._par._step

## Name: Brandon Jacobson
