# class08 notes

## reading08 notes

### Expressions and Operators

+ Assignment operators - An assignment operator assigns a value to its left operand based on the value of its right operand.

  + ex. x = 7

+ Comparison operators - A comparison operator compares its operands and returns a logical value based on whether the comparison is true.

  + Equal (==), 3 == 3
  + Not eaual (!=) var1 != 3
  + Strict equal (===) 3 === var1
  + Strict not equal (!==) 3 !== var1
  + Greater than (>) "12" > 2
  + Greater than or equal (>=) var1 >= 3
  + Lass than (<) var1 < 3
  + lass than or equal (<=) var1 <= 3

### Loops

+ For statement - A "**for**" loop repeats until a specified condition evaluates to false.

  + ex.  

  for (initialization; condition; afterthought)
  <br> statement

+ A "**for**" loop executes the following:

  1. The initializing expression initialization, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.

  2. The condition expression is evaluated. If the value of condition is true, the loop statements execute. Otherwise, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)

  3. The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.

  4. If present, the update expression afterthought is executed.

  5. Control returns to Step 2.

+ A **while** statement - A while statement executes its statements as long as a specified condition evaluates to true. (ALWAYS MAKE CONDITION EVENTUALLY FALSE. INFINITE LOOPS ARE BAD!)

Answer:

1. Expression - An expression is any valid set of literals, variables, operators, and expressions that evaluates to a single value. The value may be a number, a string, or a logical value. Conceptually, there are two types of expressions: those that assign a value to a variable, and those that simply have a value.

2. Loops create quick and easy functions so we can do something repeatedly.

3. A **for** loop stops executing when the statement is false.

4. A **while** loop will execute at least once until the statement is false unlike the for loop which wont run unless the statement is true.

## reading links

[Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)

[Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

## lab08 notes
