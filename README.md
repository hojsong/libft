# libft

[한국어 버전](README.md.kr)

## Overview
`libft` is a project that involves implementing various functions that are part of the C standard library. This project helps you understand the fundamental components of C programming, including memory management, string manipulation, and file handling.

- **Objective:** Implement standard C library functions with additional bonus features.
- **Key Features:**
  - Implements memory allocation functions.
  - Implements string manipulation functions.
  - Implements functions for handling files, output, and input.
  - Bonus functions for handling lists and more advanced operations.
  - No external libraries or dependencies required.

## Functions Implemented
Here is a list of functions that have been implemented, including bonus features:

### Memory Functions
- `ft_memset`: Fill memory with a constant byte.
- `ft_bzero`: Set memory to zero.
- `ft_memcpy`: Copy memory area.
- `ft_memmove`: Move memory area.
- `ft_memchr`: Locate a byte in memory.
- `ft_memcmp`: Compare two memory areas.

### String Functions
- `ft_strlen`: Return the length of a string.
- `ft_strdup`: Return a pointer to a newly allocated string, which is a duplicate of the original.
- `ft_strcpy`: Copy a string.
- `ft_strcat`: Concatenate two strings.
- `ft_strcmp`: Compare two strings.
- `ft_strncat`: Concatenate up to n characters from one string to another.
- `ft_strncpy`: Copy up to n characters from one string to another.
- `ft_strchr`: Locate a character in a string.
- `ft_strrchr`: Locate the last occurrence of a character in a string.
- `ft_strstr`: Locate a substring.
- `ft_strlcpy`: Copy up to size characters from one string to another.
- `ft_strlcat`: Concatenate up to size characters from one string to another.

### Additional Functions
- `ft_atoi`: Convert a string to an integer.
- `ft_itoa`: Convert an integer to a string.
- `ft_putchar_fd`: Write a character to a file descriptor.
- `ft_putstr_fd`: Write a string to a file descriptor.
- `ft_putendl_fd`: Write a string followed by a newline to a file descriptor.
- `ft_putnbr_fd`: Write an integer to a file descriptor.

### Bonus Functions
- `ft_lstnew`: Create a new list element.
- `ft_lstadd_front`: Add a new element to the front of the list.
- `ft_lstsize`: Return the size of the list.
- `ft_lstlast`: Return the last element of the list.
- `ft_lstadd_back`: Add a new element to the back of the list.
- `ft_lstdelone`: Delete a list element.
- `ft_lstclear`: Delete all elements in the list.
- `ft_lstiter`: Iterate over the list and apply a function to each element.
- `ft_lstmap`: Apply a function to each element of the list and return a new list.

## Requirements
- **Operating System:** Linux or macOS.
- **Dependencies:** None (uses only standard C libraries).

## Installation and Execution
### Clone the Repository
```bash
git clone [repository URL]
cd libft
```

### Build
```bash
make
```

### Test the Library
- You can write a program or test your functions by linking the libft.a static ibrary.

```bash
gcc -o test_program test_program.c libft.a
./test_program
```

### File Structure
- libft.h: Header file containing function prototypes.
- *.c :  Source files for the library functions.

### How It Works
- This library implements several useful functions, primarily focused on memory and string manipulation, with additional bonus features for list handling. You can link this library to any C project to make use of these functions.

### Example Usage
```c
#include "libft.h"

int main() {
    char *str = "Hello, World!";
    ft_putstr_fd(str, 1);
    return 0;
}
```

### References
- C Standard Library Documentation