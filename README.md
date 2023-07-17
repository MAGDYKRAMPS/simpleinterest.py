# simpleinterest.py
The simple interest calculator program calculates the simple interest based on the principal amount, interest rate, and time period provided by the user. The formula for calculating simple interest is:
The program takes the principal amount, interest rate per period, and time period in years as input from the user. It then calls the calculate_simple_interest function to compute the simple interest using the provided values.

The calculate_simple_interest function takes three arguments: principal, rate, and time. It validates that all the input values are positive; otherwise, it raises a ValueError. If the input values are valid, it calculates the simple interest using the formula mentioned above and returns the result.

The program uses the float function to convert user input into floating-point numbers to ensure accurate calculations. The calculated simple interest is then displayed to the user.

The program provides two examples in the documentation to demonstrate how to use the calculate_simple_interest function with different input values. The examples show the expected outputs based on the given inputs.

Note: The program assumes that the user will provide valid numerical input for principal, rate, and time. Error handling for non-numeric input is not implemented in this.
