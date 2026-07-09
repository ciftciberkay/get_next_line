*This project has been created as part of the 42 curriculum by beciftci.*

## Description
The "Get Next Line" project aims to implement a highly useful function that reads a line from a given file descriptor (`fd`). Calling this function repeatedly in a loop allows the user to read a text file one line at a time. The project emphasizes the understanding and proper usage of static variables in C programming to maintain state between function calls.

## Instructions
To compile the files and test the function, you must include the `-D BUFFER_SIZE=n` flag, where `n` is the buffer size of your choice.

Example compilation command:
```bash
cc -Wall -Wextra -Werror -D BUFFER_SIZE=42 get_next_line.c get_next_line_utils.c main.c