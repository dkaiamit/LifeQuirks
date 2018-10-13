---
title: Basics of Programming
---

# Basics of Programming

I will be using C language to demonstrate nuances shared nearly all the programs

## Primitive Data Types

These data types are offered by programming language.

### Integer | int

Integer data type represents all integers (all negative and positive numbers including 0)

```C
int a = 2; int b = -200;
```

### Character | char

Characters represent english alphabets and special symbols.
Characters have corresponding integer codes, search for ASCII codes for more details.

```C
char a = 'b'; char dollar = '$';
```

### Float | float

Float are used to store decimal values with single precision.
Double are used to store decimal values with single precision with double precision.

The word double derives from the fact that a double-precision number uses twice as many bits as a regular floating-point number.
For example, if a single-precision number requires 32 bits, its double-precision counterpart will be 64 bits long.
Source - [Stack Overflow Question](https://stackoverflow.com/questions/801117/whats-the-difference-between-a-single-precision-and-double-precision-floating-p#801146)

## Functions

Functions are great way avoid copy pasting code. It allows programmers to break logic into small pieces and execute them in efficient manner

<!-----### Method Signature----->

## Operators

Operators allow us to perform different kinds of operations on [operands](https://en.wikipedia.org/wiki/Operand). An operator is a symbol that tells the compiler to perform a certain mathematical or logical manipulation.

C operators can be classified into following types:

- Arithmetic operators (+,-,/,*,%)
- Relational operators (==,!=,>,<,>=,<=)
- Logical operators (&&,||, !)
- Bitwise operator (&, |, ^, ~, >>,<<)

### Arithmetic Operators: 
These are used to perform arithmetic/mathematical operations on operands. The binary operators falling in this category are:

Addition: The ‘+’ operator adds two operands. 
>For example, x+y.

Subtraction: The ‘-‘ operator subtracts two operands. 
>For example, x-y.

Multiplication: The ‘*’ operator multiplies two operands. 
>For example, x*y.

Division: The ‘/’ operator divides the first operand by the second. 
>For example, x/y.

[Modulus](https://en.wikipedia.org/wiki/Modulus): The ‘%’ operator returns the remainder when first operand is divided by the second. 
>For example, x%y.

The ones falling into the category of [unary](https://en.wikipedia.org/wiki/Unary_operation) arithmetic operators are:

- Increment: 

  The ‘++’ operator is used to increment the value of an integer. When placed before the variable name (also called pre-increment operator), its value is incremented instantly. 
  >For example, ++x.
  
  And when it is placed after the variable name (also called post-increment operator), its value is preserved temporarily until the execution of this statement and it gets updated before the execution of the next statement. 
  >For example, x++.

- Decrement: 

  The ‘–-‘ operator is used to decrement the value of an integer. When placed before the variable name (also called pre-decrement operator), its value is decremented instantly. 
  >For example, –-x.
  
  And when it is placed after the variable name (also called post-decrement operator), its value is preserved temporarily until the execution of this statement and it gets updated before the execution of the next statement. 
  >For example, x–-.
