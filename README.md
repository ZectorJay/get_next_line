# get_next_line
School21 project

This function read BUFFER_SIZE bytes from file per read call.
If BUFFER_SIZE is not defined it will be set to 32.

You can set BUFFER_SIZE by adding -D key during compilation.
Example:
gcc -D BUFFER_SIZE=1000 main.c get_next_line.c get_next_line_utils.c
