# Simple Interest Calculator

This is a simple interest calculator that computes the simple interest based on the principal amount, time period in years, and annual rate of interest.

## Input

- **p**: Principal amount
- **t**: Time period in years
- **r**: Annual rate of interest

## Output

Simple Interest = p * t * r

## Example

For instance, if you have a principal amount of $1000, a time period of 3 years, and an annual interest rate of 5%, you can calculate the simple interest as follows:

Simple Interest = $1000 * 3 years * 0.05 (5%) = $150

## Usage

You can use this simple interest calculator in your code to determine the interest amount for a given principal, time period, and interest rate.

```python
def calculate_simple_interest(p, t, r):
    return p * t * r

# Example usage
principal = 1000
time_period = 3
annual_rate = 0.05  # 5%
simple_interest = calculate_simple_interest(principal, time_period, annual_rate)
print(f"Simple Interest: ${simple_interest}")
