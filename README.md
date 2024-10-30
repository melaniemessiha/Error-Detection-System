# Error-Detection-System
This project implements various error-checking mechanisms for data transmission using C. The following methods are included:

1. Parity Check
2. Checksum
3. Two-Dimensional Parity Check

## Overview

The program reads data from specified files and checks for errors using the above methods. Each method outputs whether there are any errors in the transmitted data.

## Features

- **Parity Check**: Validates data using a parity bit to ensure no single-bit errors occurred during transmission.
- **Checksum**: Computes a checksum for the data and checks if it matches the expected value.
- **Two-Dimensional Parity Check**: Uses both horizontal and vertical parity checks to detect errors in a matrix of data.

## Prerequisites

- C compiler (e.g., GCC)
- Standard C libraries

## Files Required

- `White House Transmission Data - Parity.txt`
- `White House Transmission Data - Checksum.txt`
- `White House Transmission Data - 2D Parity.txt`

Make sure these files are in the same directory as the executable before running the program.

## Compilation

To compile the code, run:

```bash
gcc -o data_transmission_checker main.c

# Data Transmission Error Checking

This project implements various error-checking mechanisms for data transmission using C. The following methods are included:

1. Parity Check
2. Checksum
3. Two-Dimensional Parity Check

## Overview

The program reads data from specified files and checks for errors using the above methods. Each method outputs whether there are any errors in the transmitted data.

## Features

- **Parity Check**: Validates data using a parity bit to ensure no single-bit errors occurred during transmission.
- **Checksum**: Computes a checksum for the data and checks if it matches the expected value.
- **Two-Dimensional Parity Check**: Uses both horizontal and vertical parity checks to detect errors in a matrix of data.

## Prerequisites

- C compiler (e.g., GCC)
- Standard C libraries

## Files Required

- `White House Transmission Data - Parity.txt`
- `White House Transmission Data - Checksum.txt`
- `White House Transmission Data - 2D Parity.txt`

Make sure these files are in the same directory as the executable before running the program.

## Compilation

To compile the code, run:

```bash
gcc -o data_transmission_checker main.c
Replace main.c with the name of your C file if it's different.

#Code Structure
main(): The entry point of the program; calls the functions for each error-checking method.
parity_check(): Implements the parity check method.
checksum(): Implements the checksum validation method.
two_dimensional_parity(): Implements the two-dimensional parity check.
read_parity_check(): Reads the parity check data from a file.
read_checksum(): Reads the checksum data from a file.
read_two_dimensional_parity(): Reads the two-dimensional parity data from a file.
p_binary(): Helper function to print binary representation of values.

#Example Output
** Part 1 - Parity Check Processing **

Data stream:
1 0 1 1 0 1 0 0
Parity byte: 1
...
Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for improvements or bugs.

License
This project is licensed under the MIT License - see the LICENSE file for details.
