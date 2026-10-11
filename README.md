
# C Mini Preprocessor

A C-based mini preprocessor developed to understand the basic preprocessing operations performed on C source files.

## Overview

The C Mini Preprocessor is a project that demonstrates how a C source file can be processed before compilation. It focuses on comment removal, header file inclusion, and macro collection and replacement using C programming and file handling.

## Features

The project focuses on three main preprocessing operations:

1. **Comment Removal**
   - Identifies and removes comments from a C source file.
   - Handles single-line and multi-line comments, if implemented.

2. **Header File Inclusion**
   - Identifies header file inclusion directives.
   - Processes header files according to the implementation.

3. **Macro Collection and Replacement**
   - Identifies macro definitions.
   - Collects macro names and their associated values.
   - Replaces macro occurrences in the source file, where applicable.

## Project Workflow

The general processing flow is:

Input C File (`.c`)
↓
Comment Removal
↓
Header File Inclusion
↓
Macro Collection
↓
Macro Replacement
↓
Preprocessed Output File (`.i`)

## Technologies Used

- C Programming
- File Handling
- String Manipulation
- Make Utility
- Git and GitHub

## Project Structure

The project may contain the following types of files:

- `main.c` — Main program and processing flow
- `*.c` — Source files implementing preprocessing operations
- `*.h` — Header files, if required
- `make_file` — Build instructions, if configured with this filename
- `README.md` — Project documentation
- `.gitignore` — Files excluded from version control

Update this section to reflect the actual filenames in the repository.

## Compilation

Compile the project using GCC:

```bash
gcc main.c comments_removal.c headerfile_inclusion.c macro_replacement.c -o my_preprocessor
```
## Execution

Run the generated executable using the appropriate command for your operating system.

For example, on Linux:

```bash
./a.out
```

The executable name and input-file requirements depend on the implementation.

## Concepts Demonstrated

- C programming fundamentals
- File input and output operations
- String processing
- Preprocessor directives
- Macro handling
- Source code transformation
- Compilation and build automation

## Learning Outcomes

This project helps develop an understanding of how source files can be processed before compilation and provides practical experience with file handling and text processing in C.

## Output

The program generates an intermediate preprocessed file named `abc.i`.

The generated executable `my_preprocessor` and intermediate file `abc.i` are excluded from the GitHub repository using `.gitignore`.


## Author

Pratheek S K
