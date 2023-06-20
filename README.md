# get_next_line

Welcome to get_next_line! This is a project from the 42 programming school that aims to read and return a line from a file descriptor. The goal of this project is to create a function that allows you to read text from a file or any other input source, one line at a time.

## Getting Started

To use the get_next_line function, you can clone the repository and compile the `get_next_line.a` library by running the `make` command:

```bash
git clone https://github.com/hovhannisyangevorg/get_next_line.git
```
```bash
cd get_next_line
```
```bash
make
```


This will compile the source files and create the `get_next_line.a` library file.

You can then link this library to your own projects by including the `get_next_line.h` header file and adding the library path and name (`-L/path/to/get_next_line -lget_next_line`) to your compilation command.

## Project Structure

The project is organized as follows:

- `Makefile`: Contains the compilation rules for building the library.
- `get_next_line.h`: The library's header file, which includes the necessary function prototype.
- `get_next_line.c`: The source code file that implements the get_next_line function.
- `get_next_line_utils.c`: Additional utility functions used by get_next_line.
- `include/`: Directory containing additional header files used internally by the library.
- `obj/`: Directory where the object files will be created during compilation.
- `src/`: Directory containing the source code files for get_next_line and supporting functions.
## Usage

To use the get_next_line function, you need to provide a file descriptor (e.g., from `open` or `stdin`) and a pointer to a character pointer. The function will read from the file descriptor and store the line in the character pointer. The function returns 1 when a line is successfully read, 0 when the end of file is reached, and -1 in case of an error.

Please refer to the provided `get_next_line.h` header file for detailed usage information and examples.

## Documentation

The `get_next_line.h` header file contains the function prototype and any necessary definitions for using get_next_line. Please consult this file to understand how to use the function and its return values.




