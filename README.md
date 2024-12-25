# C# Runtime Exception: Accessing Non-Existent Property

This repository demonstrates a common C# runtime error that occurs when attempting to access a property that does not exist within a class.  The error is not caught during compilation, leading to unexpected runtime exceptions.  The `bug.cs` file shows the erroneous code, while `bugSolution.cs` provides the corrected version.

## Bug Description
The bug occurs when the `MyMethod` function tries to access `NonExistentProperty`, which is not defined in the `ExampleClass` class. This results in a `RuntimeBinderException` at runtime.  This type of error can be challenging to debug because it does not appear during compilation.

## Solution
The solution is to ensure that all properties accessed within the class are correctly defined.   Proper use of the IDE's auto-completion and thorough testing can help prevent such errors.