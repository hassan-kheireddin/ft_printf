# ft_printf

[![42 École](https://img.shields.io/badge/42-École-000000?style=flat&logo=42&logoColor=white)](https://42.fr)

The `ft_printf` project is a reimplementation of the C standard library function `printf`. It was developed as part of the 42 École curriculum to deepen the understanding of variadic functions, formatting, and low-level output.

---

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Getting Started](#getting-started)
---

## About the Project

`ft_printf` replicates the behavior of the `printf` function from the C standard library. This project involves implementing a function capable of formatted output for various data types, including integers, characters, and strings.

The project focuses on:
- Understanding and managing variadic functions.
- Handling different format specifiers like `%d`, `%s`, `%x`, etc.
- Memory and buffer management for efficient output.

---

## Features

- Supports the following format specifiers:
  - `%c` : Single character.
  - `%s` : String.
  - `%d` / `%i` : Signed decimal integer.
  - `%u` : Unsigned decimal integer.
  - `%x` / `%X` : Hexadecimal (lowercase/uppercase).
  - `%%` : Prints a literal `%`.
- Manages flags like width and precision for formatted output.
- Includes comprehensive testing for edge cases.

---

## Getting Started

### Prerequisites
- A Unix-based operating system (Linux or macOS recommended).
- GCC or another compatible C compiler.
- Make utility.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ft_printf.git
   ```
2. Enter the folder:
   ```bash
   cd ft_printf
   ````
4. Compile:
   ```bash
   make
