*This project has been created as part of the 42 curriculum by beciftci.*

# Get Next Line

## Description

`get_next_line(int fd)` reads one line from an open file descriptor per call. It keeps unread bytes for the next call, includes the newline when present, and returns `NULL` at end of file or on error. Free each returned line when you finish using it. Read one descriptor at a time with this implementation.

## Instructions

Include [get_next_line.h](./get_next_line.h) in your own `main.c`. Compile the driver with both source files.

```sh
cc -Wall -Wextra -Werror -D BUFFER_SIZE=42 main.c get_next_line.c get_next_line_utils.c -o demo
```

The header defaults to a `BUFFER_SIZE` of 42 bytes. Set a different positive size with the compiler flag above.
