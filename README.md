# Ignoring Errors in Go

This repository demonstrates a common error in Go programs: ignoring the error returned by a function.

The `bug.go` file contains a function `calculate` that performs division. If the divisor is zero, it returns an error. However, the `main` function fails to check for this error, leading to unexpected behavior or even a program crash.

The `bugSolution.go` file provides a corrected version, showing how to properly handle errors.