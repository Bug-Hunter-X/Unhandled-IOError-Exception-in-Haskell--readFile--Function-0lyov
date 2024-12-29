# Unhandled IOError Exception in Haskell `readFile`
This repository demonstrates an example of an unhandled `IOError` exception in Haskell when using the `readFile` function.  The original code lacks error handling, which can lead to program crashes if the specified file is not found or accessible. The solution demonstrates how to properly handle this exception using pattern matching.

## Bug
The `bug.hs` file contains the erroneous code.  It attempts to read a file without handling potential errors.

## Solution
The `bugSolution.hs` file shows the corrected code, which uses a `catch` block to handle `IOError` gracefully.