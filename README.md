# Libft

## Project Overview

Libft is your very first own library project in C programming, aiming to recreate several standard C library functions as well as adding a few additional useful functions. This project allows you to understand the inner workings and implementations of commonly used functions, providing a solid foundation for future C projects.

## Features

- **Libc Functions**: A collection of re-coded functions from the standard C library (`libc`), such as `strlen`, `memset`, and `strdup`, to understand their behavior.
- **Additional Functions**: Implementation of functions that are either not present in `libc` or presented in a different form. These include functions for manipulating memory, strings, and list data structures.
- **List Manipulation**: As part of the bonus section, functions for handling linked lists are included, enabling operations such as adding, removing, and iterating over list elements.

## Installation

Clone the repository and compile the library using the provided Makefile:

```bash
make
```

This command compiles the library and creates a `libft.a` file, which you can include in your C projects.

## Usage

To use the `libft` functions in your project, include the header file `libft.h` in your C files and compile your project with the `libft.a` library.

Example of including the library in your C file:

```c
#include "libft.h"
```

Compilation example:

```bash
gcc your_c_file.c -L. -lft
```
