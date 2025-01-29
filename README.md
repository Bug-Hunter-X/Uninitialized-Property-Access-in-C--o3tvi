# Uninitialized Property Access in C#

This repository demonstrates a common error in C#: accessing a property before it has been initialized. This can lead to unpredictable results or exceptions.

## The Bug

The `bug.cs` file contains a class with a property that is not initialized before it is accessed.  This results in undefined behavior.

## The Solution

The `bugSolution.cs` file provides a corrected version where the property is initialized before being accessed.  This ensures predictable results.

## How to Run

1. Clone this repository.
2. Compile and run `bug.cs` and `bugSolution.cs` using your preferred C# compiler and runtime (e.g., .NET SDK).

Observe the difference in output.