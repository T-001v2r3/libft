# 42 Libft

Welcome to 42 Libft! This project is a fundamental piece of the curriculum at 42, aiming to introduce you to the basics of C programming. The goal is to build your own library of functions that you will be able to reuse throughout your journey at 42.

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

## Introduction

The libft project requires you to create your own implementation of some standard C library functions, as well as additional utility functions that you may find useful later on. By completing this project, you'll gain a deeper understanding of how these functions work and improve your skills as a programmer.

## Getting Started

To get started with libft, simply clone this repository to your local machine:

```bash
git clone https://github.com/T-001v2r3/libft.git
```
Once you have the repository cloned, you can compile the library by running:

```bash
make # to build without bonus functions
make bonus # to build with bonus functions
make re # to re-build the project
```
If you want to delete the compiled files:

```bash
make clean # to clean up objects
make fclean # to clean up everything
```
This will generate the libft.a static library, which you can then link to your projects.
Usage

To use the functions in your projects, simply include the libft.h header file and link against the libft.a library. For example:

```c

#include "libft.h"

int main() {
    ft_putstr("Hello, world!\n");
    return 0;
}
```
Compile your program with the libft library:

```bash

cc -o my_program my_program.c -L. -lft
```
## Contributing

Contributions to libft are welcome! If you have ideas for new functions or improvements to existing ones, feel free to open an issue or submit a pull request.

Before submitting a pull request, please make sure your code follows the 42 Norm coding style.

## License

This project is licensed under the terms of the MIT license.
