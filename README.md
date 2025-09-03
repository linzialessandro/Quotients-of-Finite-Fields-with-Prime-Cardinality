# Krasner Quotient Hyperfield Construction and Analysis

This notebook provides a set of Python programs to construct, analyze, and compare Krasner quotient hyperfields obtained from finite fields $\mathbb{F}_p$ modulo a multiplicative subgroup.

## Overview

The notebook is structured into four main parts:

1.  **Krasner Quotient Hyperfield Construction over Prime Fields**: This section contains the core program for constructing a quotient hyperfield from $\mathbb{F}_p$ modulo a multiplicative subgroup of order $d$. It computes and displays the additive hyperoperation table, characteristic, and c-characteristic of the resulting hyperfield.

2.  **Generating pairs $(p,d)$ for a given order $n$**: This program helps in finding pairs of a prime $p$ and a divisor $d$ of $p-1$ such that the resulting quotient hyperfield has a desired order $n$.

3.  **Isomorphism check**: This program implements a method to check if two quotient hyperfields, given by their defining pairs $(p,d)$, are isomorphic.

4.  **Visualizing characteristics data**: This program combines the functionalities of the previous sections to generate pairs $(p,d)$ for a given order $n$ and maximum prime $max_p$, group the resulting hyperfields into isomorphism classes, compute the characteristic and c-characteristic for each class, and visualize the distribution of these characteristics.

## Features

- Pure Python implementation using modular arithmetic.
- Construction of multiplicative subgroups and coset representatives.
- Computation and visualization of additive hyperoperation tables.
- Calculation of characteristic and c-characteristic of the hyperfields.
- Tools for finding pairs $(p,d)$ for a given hyperfield order.
- Isomorphism checking based on additive hyperoperation tables.
- Visualization of characteristic and c-characteristic distributions across isomorphism classes.

## Requirements

- Python 3.x standard environment.
- `pandas` for displaying tables.
- `sympy` for prime number generation (`primerange`).
- `matplotlib` for plotting visualizations.
- `numpy` for plotting adjustments.

These libraries should be available in a standard Google Colab environment.

## How to Use

Run the cells sequentially. The programs that require user input will prompt you to enter the necessary values (e.g., prime $p$, divisor $d$, desired order $n$, maximum prime $max_p$).

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) file for details.
