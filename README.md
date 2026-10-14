# C--program8

# Addition of Two Integers Using a User-Defined Function in C

## 1. Description
This C program accepts two integers from the user and calculates their sum using a user-defined function named `Addition()`.

## 2. Problem Statement
Accept any two integers from the user, perform addition, and display the result.

## 3. Algorithm
1. Start.
2. Accept the first number as `No1`.
3. Accept the second number as `No2`.
4. Create a variable `Ans` to store the result.
5. Perform addition and store the result in `Ans`.
6. Display the result.
7. Stop.

## 4. Function Details

| Property | Details |
|---|---|
| Function Name | `Addition()` |
| Input | Two integers |
| Output | Integer |
| Description | Performs addition |
| Programming Language | C |

## 5. Sample Output

```text
Enter first number :
10
Enter second number :
11
Addition is : 21
```

## 6. Test Cases

| Input 1 | Input 2 | Expected Output |
|---:|---:|---:|
| 10 | 11 | 21 |
| 11 | 0 | 11 |
| 0 | 11 | 11 |
| 20 | -9 | 11 |
| -9 | 20 | 11 |
| -20 | -11 | -31 |

## 7. Concepts Used
- User-defined functions
- Function arguments and return values
- Integer variables
- User input using `scanf()`
- Output using `printf()`
- Function calls
- Testing with positive, negative, and zero values

## 8. Compilation and Execution

Compile using GCC:

```bash
gcc program.c -o program
```

Run on Windows:

```bash
program.exe
```

Run on Linux/macOS:

```bash
./program
```

## 9. Author
**Sakshi Sandip Kamthe**

## 10. Conclusion
This program demonstrates how to perform addition using a user-defined function in C. The `Addition()` function accepts two integer arguments, calculates their sum, and returns the result to the `main()` function. The program is tested with positive, negative, and zero values.
