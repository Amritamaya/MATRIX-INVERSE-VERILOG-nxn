# Matrix Inversion in Verilog

# Overview

This repository contains a Verilog implementation of matrix inversion using the Gaussian-Jordan elimination method. The module supports fixed-point arithmetic for better numerical precision and is parameterized to handle different matrix sizes and bit widths.

# Features

*Implements Gaussian-Jordan elimination for matrix inversion.

*Supports fixed-point arithmetic with configurable fractional bits.

*Parameterized matrix size .

*State-machine-based control flow for efficient execution.

*Augmented matrix approach for inversion computation.





# Description

# Finite State Machine (FSM)

The module operates using an FSM with the following states:

IDLE: Waits for the start signal.

INIT_AUGMENT: Initializes the augmented matrix.

FIND_PIVOT: Finds the pivot element for the current column.

SWAP_ROWS: Swaps rows if necessary to handle zero pivots.

NORMALIZE_ROW: Normalizes the pivot row.

ELIMINATE_COL: Eliminates other rows to form an identity matrix.

BACK_SUBST: Extracts the inverse matrix from the augmented form.

# Author

Developed by **Amrin Jalaludheen**, **Amrita M** , **Sudev S**

