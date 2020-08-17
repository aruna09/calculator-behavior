# Addition

Scenario: Addition of two positive numbers

  Given: the calculator is ON

  When: I type in the two numbers and the operator
  
  Then: I see the result

Scenario: Addition of two negative numbers
  
  Given: the calculator is ON
  
  When: I type two negative numbers
  
  Then: display the result of addition
  
Scenario: Addition of fractions
  
  Given: the calculator is ON
  
  When: I enter two fraction operands
  
  Then: display result of addition in fractions/decimals

Scenario: Addition of positive and negative number
  
  Given: the calculator is ON
  
  When: Add one positive and negative operand
  
  Then: Display the result of the addition.

Scenario: Addition of decimals
  
  Given: the calculator is ON
  
  When: Add Decimal numbers
  
  Then: display the result of the addition
  
Scenario: Typing operator more than once
  
  Given: the calculator is ON
  
  When: the user enters more than one operator
  
  Then: Alert user about the discrepancy

Scenario: Addition of more than 2 numbers
  
  Given: the calculator is ON
  
  When: the user enters more than two numbers
  
  Then: perform addition on all the provided operands.

Scenario: Adding numbers where the result goes out of range

  Given: the calculator is ON
  
  When: the user enters two large numbers operands.
  
  Then: Alert user of "Number too large" and show a shortened version of the result.

Scenario: User gives 6+* as input?

  Given: the calculator is ON
  
  When: user gives wrong input
  OR enters one operand
  OR enters operators at wrong places
  
  Then: Alert the user about the Wrong Input
  
Scenario:Identify operation

  Given: the calculator is ON
  
  When: user enters an operator
  
  Then: able to identify the operator

Scenario: Converse operation

  Given: the calculator is ON
  
  When: I type operand 2 + operand 1
  
  Then: I get the same answer as that of operand 1 + operand 2
