# get_next_line
# read() function
```size_t read(int fd, void *buf, size_t cnt);``` <br>
This function read specific amount of bytes **cnt** of input into memory area indicated by **buf** <br>
+ Header file define read() : ```#include <unistd.h>```
+ fd : file descriptor of the file from which data is to be read
+ buf: buffer to read data from
+ cnt: length of the buffer
