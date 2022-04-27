# Status
We should all be reading Chapter 7 for now so we know how to approach the problem.

## Abi

## Owen
hi

## Akshay
- Finished reading Chapter 7 (message for notes!)
- Wrote preliminary buggy code to generate Hermite Polynomials
- Wrote some math that can be added to the repository later

## Nina

# Hermite-Convolutions
For solving the computational challenge in module 6 of 2021-22 Ted's Linear Alegbra class

## Problem Restatement
This was copied from a local Obsidian file on Akshay's computer. He'll add a live version to this repository if he figures out how.

### Hermite Polynomials
Hermite Polynomials are an orthonormal basis of the function space defined recursively by$$h_{k+1}x = \left[\left(x-\frac{\text{d}}{\text{dx}}\right)h_{k}x\right] h_0(x) = 1;$$the following function generates the Hermite Polynomials up to a degree determined by the user. For instance, $$h_1(x) = \left[\left(x-\frac{\text{d}}{\text{dx}}\right)h_0(x)\right]$$ $$= \left[x(1)-\frac{\text{d}}{\text{dx}}1\right]$$$$= x$$ Likewise, $$h_2(x) = x^2 - 1$$ and so on and so forth.

# Results
When we add results we'll add them here. The Jupyter Notebook will contain all the nitty-gritty derivations but this will serve as a summary.
