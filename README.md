# Unhandled Operation in Calculator Function

This repository demonstrates a common JavaScript error related to unhandled operations in a switch statement.  The `calculate` function performs basic arithmetic operations (+, -, *, /), but it doesn't handle any other input correctly.  The `bug.js` file contains the buggy code.  The `bugSolution.js` file provides a corrected version that handles invalid operations more gracefully.

## Bug Description

The primary issue is that the `switch` statement in the `calculate` function lacks a robust mechanism to handle cases where the input `operation` is not one of the four expected arithmetic operators. This results in an unhandled exception being thrown when an unexpected operation is passed.