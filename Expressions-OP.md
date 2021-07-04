# Operators
>JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

- Assignment operators
- Comparison operators
- Arithmetic operators
- Bitwise operators
- Logical operators
 - String operators
- Conditional (ternary) operator
- Comma operator
- Unary operators
- Relational operators

## Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.

There are also compound assignment operators that are shorthand for the operations listed in the following table:

## Comparison operators
A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. The following table describes the comparison operators in terms of this sample code:

## Arithmetic operators
An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity).

## Bitwise operators
A bitwise operator treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers. For example, the decimal number nine has a binary representation of 1001. Bitwise operators perform their operations on such binary representations, but they return standard JavaScript numerical values.


# Loops and iteration

###  for statement
>A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

>A for statement looks as follows:

>for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

 ###  do...while statement

>The do...while statement repeats until a specified condition evaluates to false.

>A do...while statement looks as follows:

>do
  statement

> while (condition);


###  while statement
>A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

>while (condition)
  statement



  ###  for...in statement
>The for...in statement iterates a specified variable over all the enumerable properties of an object. For each distinct property, JavaScript executes the specified statements. A for...in statement looks as follows:

>for (variable in object)
  statement
