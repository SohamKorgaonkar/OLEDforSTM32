**I2C OLED Libraries for STM32F4 Discovery Board using HAL_I2C**

*This is a modified version of I2C OLED Library by  Olivier Van den Eede(4ilo)*

1. This library uses HAL library so can be easily used with CubeMX
2. Supports bitmap for generating images

**How to use**
1. Generate a precode using CubeMX
2. Add the files in the respective folders (.h files in inc and .c files in src)
3. Include the file in the project using `#include "ssd1306.h"` and `#include "fonts.h"`

**Functions and their uses**
All functions and their uses are defined in the ssd1306.c file.

