# Simple Interest Calculator

## Description

The Simple Interest Calculator is a simple program that calculates the simple interest based on the principal amount, rate of interest, and time period.

## Formula

Simple Interest = (Principal × Rate × Time) / 100

## Input

The calculator requires the following inputs:

* Principal amount
* Rate of interest
* Time period in years

## How to Use

1. Enter the principal amount.
2. Enter the rate of interest.
3. Enter the time period in years.
4. The calculator calculates and displays the simple interest.

## Example

If the principal amount is 1000, the rate of interest is 5%, and the time period is 2 years:

Simple Interest = (1000 × 5 × 2) / 100

Simple Interest = 100

## Bash Code Example

```bash
simple_interest=$(echo "scale=2; ($principal * $rate * $time) / 100" | bc)
echo "Simple Interest: $simple_interest"
```

## Purpose

This project demonstrates a simple interest calculator using basic Bash scripting and mathematical calculations.
