# Division

Scenario: Division by 0 when operand 1 is any number

  Given: calculator is ON

  When: When the second Operand is 0

  Then: Display Alert "Wrong operand"

Scenario: Divide 0 by any number

Given: calculator is ON

When: the first Operand is 0

Then: Display 0

Scenario: Division isn't symmetric

Given: calculator is ON

When: both operands are different

Then: Result calculated is not the same

Scenario: Division when both operands are 0

Given: calculator is ON

When: both the operands are 0

Then: Display result as 0

Scenario: Recurring decimal case

Given: calculator is ON

When: the answer of the division has more than two decimal digits

Then: Display result with two decimal places

Scenario: User presses "/" more than one time

Given: calculator is ON

When: user enters division operators

Then: Display result obtained with one division

Scenario: When operand 2 is not present

Given: calculator is ON

When: User enters one operand

Then: Prompt user to enter Operand 2

Scenario: Division by any/all operands being fractions

Given: calculator is ON

When: user enters 2 division operators

Then: Convert fraction to decimal and
compute the result of the division

Scenario: Division of more than one number

Given: calculator is ON

When: User enters more than two
division operators and operands

Then: Compute result from right to left
and display the final result
