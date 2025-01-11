# Swift Argument Label Error
This repository demonstrates a common error in Swift related to argument labels.  When calling functions with external parameter names, all of the labels must be included, otherwise a compile-time error will occur.

The `bug.swift` file contains code exhibiting the error. The `bugSolution.swift` file shows how to correct the error.

## How to Reproduce
1. Clone this repository.
2. Open `bug.swift` in Xcode.
3. Attempt to compile the code.  You will encounter a compiler error. 

## Solution
The solution lies in correctly using argument labels. Refer to `bugSolution.swift` for the correct implementation.