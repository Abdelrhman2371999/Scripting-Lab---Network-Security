# Day 1: C Programming Fundamentals

This directory contains basic C programming exercises focusing on clean code practices and modular design.

## 📁 Files

### 1. `calculator.c` 
A multi-functional calculator program that demonstrates:
- Basic input/output operations
- Function definitions and calls
- Control structures (if-else, while loops)
- Mathematical operations

**Features:**
- Calculate area of rectangle
- Convert Fahrenheit to Celsius
- Grade evaluation system
- Multiplication table generator

### 2. `calculator_refactored.c`
An improved version of the calculator with:
- Better function names and structure
- Input validation
- Error handling
- Modular design
- Comprehensive comments

## 🚀 Compilation & Execution

```bash
# Compile the basic version
gcc calculator.c -o calculator -Wall -Wextra

# Compile the refactored version
gcc calculator_refactored.c -o calculator_refactored -Wall -Wextra

# Run the program
./calculator
./calculator_refactored