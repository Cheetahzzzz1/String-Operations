# String-Operations

# Overview

This project implements two core functionalities using stack data structure:-

1. **Valid Parentheses** : Determines if a given string of parentheses is correctly balanced.

2. **Postfix Expression Evaluator** : Evaluates arithmetic expressions written in Postfix notation.

Both classes uses a custom 'stack' for better processing.

# Stack Implementation

The Stack class provides basic stack operations:

1. push(item) : Adds an item to the stack.

2. pop() : Removes an item from the stack

3. peek() : Returns the top item without removing it.

4. is_empty() : Checks if the stack is empty.

This class is used in both solutions to efficiently manage data.

# Features

<ins> Valid Parentheses Checker </ins>

1. Accepts a string containing only (), {}, [].

2. Uses a stack to track open brackets and validates closing brackets.

3. Returns True if the string is correctly balanced, otherwise, False.

<ins> Postfix Expression Evaluator</ins>

1. Accepts a postfix expression string.

2. Uses a stack to evaluate arithmetic expressions using +, -, *, /

3. Ensures integer division where applicable.

4. Returns the computed result.

# Dependencies

1. Python 3.x

2. CSV module (built-in).

# Notes

1. The CSV files should be properly formatted with valid expressions.

2. The program ensures handling of special characters like UTF-8 BOM when reading CSV files.
