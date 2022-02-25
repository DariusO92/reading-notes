# Operators and Loops

## Operators

JavaScript has the following types of operators.
- Assignment
- Comparison
- Arithmetic
- Bitwise
- Logical
- String
- Conditional (ternary)
- Comma
- Unary
- Relational

 JavaScript has both binary and unary operators and one special ternary operator, the conditional operator.

 A binary operator requires two operands, one before the operator and one after the operator.

 ### Assignment

  An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

 ###  Comparison

  A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.

  ## Loops

   Loops offer a quick and easy way to do something repeatedly

   1 The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
   2 The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
   3 The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
   4 If present, the update expression incrementExpression is executed.
   5 Control returns to Step 2.



