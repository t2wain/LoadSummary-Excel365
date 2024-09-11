## Excel 365 - Programming with LAMBDA

With Excel 365, we can now create custom functions using LAMBDA instead of VBA. This project explores the programming paradigm when creating custom functions with LAMBDA.

Data types available:

- Primitive data types include string, number, and boolean
- Complex data type include 2D array

Language features:

- All data is immutable
- Allow recursive function call
- Allow optional parameters
- Un-typed parameter / variable

Main language constructs:

- LET
- LAMBDA
- IF

## Electrical Load Summary

Electrical Load Summary is an engineering worksheet to calculate the total electrical load of an electrical system. Electrical loads are powered by buses and buses are powered by other buses (parent buses). The objective is to calculate the connected loads of each bus and the rollup loads from other buses that it powers.

The objective of this exercise is to use the new features of Excel 365 to perform the calculation with custom LAMBDA functions and to avoid VBA. File [LoadSum_LAMBDA.txt](./LoadSum_LAMBDA.txt) list the custom LAMBDA functions used in this worksheet.