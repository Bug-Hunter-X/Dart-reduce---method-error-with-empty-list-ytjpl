# Dart Reduce() Method and Empty Lists

This repository demonstrates a common error encountered when using the `reduce()` method in Dart with an empty list. The `reduce()` method requires at least one element in the list to perform the reduction operation. Attempting to use it on an empty list will result in a runtime error.

The `bug.dart` file shows the error, while `bugSolution.dart` provides a solution using a check for an empty list before calling `reduce()`.