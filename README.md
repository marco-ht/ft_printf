# ft_printf

This repository contains my implementation of the **ft_printf** project, developed as part of the 42 School curriculum. The goal of this project is to recreate the functionality of the standard `printf` function in C, while adhering to the strict coding standards and best practices required by the 42 School. This project is intended solely for demonstration purposes to showcase my programming skills.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Acknowledgments](#acknowledgments)
- [Disclaimer](#disclaimer)
- [License](#license)

## Overview

The **ft_printf** project is a custom implementation of the standard C library function `printf`. The project involves parsing format strings, handling various conversion specifiers, and outputting formatted data. This project was developed to reinforce knowledge of C programming, string manipulation, and variable argument handling.

## Project Structure

The repository is organized as follows:

```
ft_printf/
├── includes/    # Header files containing function prototypes and macros
├── srcs/        # Source files implementing the ft_printf functionality
├── Makefile     # Makefile for compiling the project
└── README.md    # This file
```

- **includes/**: Contains header files used across the ft_printf implementation.
- **srcs/**: Contains the source code files, including the main ft_printf function and helper functions.
- **Makefile**: Automates the build process for ease of compilation.

## Installation

To build the ft_printf project, follow these steps:

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/ft_printf.git
   cd ft_printf
   ```

2. **Compile the project:**

   Simply run:

   ```sh
   make
   ```

   This command will compile the project and generate a static library file (libftprintf.a).

## Usage

After successfully compiling the project, you can use ft_printf as follows:

### Including in your own C projects:

Include the header file in your code:

```c
#include "ft_printf.h"

int main(void) {
    ft_printf("Number: %d, String: %s, Character: %c\n", 42, "example", 'A');
    return 0;
}
```

Compile your code by linking the libftprintf.a library.

## Features

- **Format Parsing**: Supports format specifiers such as %c, %s, %p, %d, %i, %u, %x, %X, and %%.
- **Variable Arguments**: Uses the stdarg library to handle a variable number of arguments.
- **Robust Error Handling**: Includes checks and balances to handle incorrect or edge-case input formats.
- **Modular Code Design**: Organized into multiple source files for better code maintainability and readability.
- **Customizable Output**: Designed to closely mimic the behavior of the standard printf, with room for further enhancements.

## Acknowledgments

- Thanks to the 42 community and mentors for their guidance and support.
- Special thanks to contributors of similar projects and open-source communities for sharing valuable resources.
- Gratitude to those who have reviewed my code and provided constructive feedback.

## Disclaimer

**IMPORTANT**:
This project was developed solely as part of the educational curriculum at 42 School. The code contained in this repository is published only for demonstration purposes to showcase my programming capabilities.

**Academic Integrity Notice**:
It is strictly prohibited to copy or present this code as your own in any academic submissions at 42 School. Misuse or uncredited use of this project is considered a violation of the 42 academic regulations.

## License

This repository is licensed under the Creative Commons - NonCommercial-NoDerivatives (CC BY-NC-ND 4.0) license. You are free to share the repository as long as you:

- Provide appropriate credit.
- Do not use it for commercial purposes.
- Do not modify, transform, or build upon the material.

For additional details, please refer to the CC BY-NC-ND 4.0 license documentation.

Developed with dedication and in strict adherence to the standards of 42 School.
