# _printf

A formatted output conversion C program was completed as part of the low-level programming and algorithm track at Holberton School. The program is a pseudo- recreation of the C standard library function, ```printf```.

## Dependencies 👫

The ```_printf``` function was coded on an Ubuntu 14.04 LTS machine with ```gcc``` version 4.8.4.

## Usage

To use the ```_printf``` function, assuming the above dependencies have been installed, compile all ```.c``` files in the repository and include the header ```main.h``` with any main function.

### Example ```main.c```:

```bash
#include "main.h"

int main(void)
{
    _printf("Hello, World!");

    return (0);
}
```

### Compilation:
```bash
$ gcc *.c -o tester
```

### Output:

```bash
$ ./tester
Hello, World!
$
```
## Description 💬
The function ```_printf``` writes output to standard output. The function writes under the control of a ```format``` string that specifies how subsequent arguments (accessed via the variable-length argument facilities of ```stdarg```) are converted for output.

Prototype: ``` int _printf(const char *format, ...);```


## Return Value
Upon successful return, ```_printf``` returns the number of characters printed (excluding the terminating null byte used to end output to strings). If an output error is encountered, the function returns ```-1```.

## License
[MIT](https://choosealicense.com/licenses/mit/)
