# Multiplication

Scenario: Result overflow

Given:calculator is ON

When: user enters a number with more than 6 digits

Then:display result in words

Scenario: Signs of the numbers

Given:calculator is ON

When: user enters numbers with different signs

Then:multiply numbers and signs
separately and display answer

Scenario: Zero value multiplication

Given:calculator is ON

When: user enters 0 as operand

Then: display 0

Scenario: Multiplication by 1

Given:calculator is ON

When: user enters 1 as operand 1

Then: display operand 2

Scenario: Decimal value multiplication

Given:calculator is ON

When:user enters two decimal values

Then:display result with two digits after decimal point

Scenario: Simple multiplication

Given:calculator is ON

When: user enters two operands

Then:display result of multiplication

Scenario: Decimal & integer multiplication

Given:calculator is ON

When: user enters a mixture of decimal and integers numbers

Then: display the result with two digits after decimal

Scenario: More than two numbers multiplication

Given:calculator is ON

When: user enters more than two operands

Then: multiply all operands and display result

Scenario: Complex number multiplication

Given:calculator is ON

When: user enters complex numbers

Then: display result of complex number multiplication

Scenario: Range of operand exceeds allowed limit

Given:calculator is ON

When: user enters more than a defined number of operands

Then: Alert user "Reduce operands"

Scenario: Pressing "multiply button" more than one time

Given:calculator is ON

When: user enters multiply button more than one time

Then: display result with multiplication

Scenario: Interleaving operators

Given:calculator is ON

When: user enters more than one operator

Then: display result with the last operand

Scenario: Capping the Decimal value

Given: calculator is ON

When: user enters decimal operands

Then: cap the value of the answer
to two digits after the decimal point
