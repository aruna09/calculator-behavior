# Addition

Scenario: Addition of two positive numbers

  Given: the calculator is turned ON

  When: I type in the two numbers and the operator
  
  Then: I see the result

Scenario: Addition of two negative numbers
  
  Given: the calculator is turned ON
  
  When: I type two negative numbers
  
  Then: result of the addition is displayed
  
Scenario: Addition of fractions
  
  Given: the calculator is turned ON
  
  When: I enter two fraction operands
  
  Then: result of the addition is displayed in fractions/decimals

Scenario: Addition of positive and negative number
  
  Given: the calculator is turned ON
  
  When: one positive and another negative operands are added
  
  Then: Display the result of the addition.

Scenario: Addition of decimals
  
  Given: the calculator is turned ON
  
  When: Decimal numbers are added as operands
  
  Then: display the result of the addition
  
Scenario: Typing operator more than once
  
  Given: the calculator is turned ON
  
  When: multiple operators are given instead of a single operator
  
  Then: Alert user about the discrepency and allow user to enter again.

Scenario: Addition of more than 2 numbers
  
  Given: the calculator is turned ON
  
  When: more than two number are added
  
  Then: perform addition on all the provided operands.

Scenario: Adding numbers where the result goes out of range

  Given: the calculator is turned ON
  
  When: two large numbers are entered as operands.
  
  Then: Alert user of "Number too large" and show a shortened version of the result.

Scenario: 6+* is provided as input?

  Given: the calculator is turned ON
  
  When: wrong input is provided
  OR only one operand is provided instead of two
  OR operators given at wrong places
  
  Then: Alert the user about the Wrong Input
  
Scenario:Identify operation

  Given: the calculator is turned ON
  
  When: an operator is entered
  
  Then: able to identify the operator

Scenario: Converse operation

  Given: the calculator is turned ON
  
  When: I type operand 2 + operand 1
  
  Then: I get the same answer as that of operand 1 + operand 2
