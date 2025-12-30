# Simple Interest Calculator

## Description
This project explains a simple interest calculator that computes the
simple interest based on principal amount, rate of interest, and time.

## Formula
Simple Interest = (Principal × Rate × Time) / 100

## Example
If:
- Principal = 1000
- Rate = 5%
- Time = 2 years

Simple Interest = (1000 × 5 × 2) / 100 = 100

## Sample Code (Python)
```python
def simple_interest(p, r, t):
    return (p * r * t) / 100

print(simple_interest(1000, 5, 2))
