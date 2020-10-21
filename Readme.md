**I2C OLED Libraries for STM32F4 Discovery Board using HAL_I2C**

*This is a modified version of I2C OLED Library by  Olivier Van den Eede(4ilo)*

1. This library uses HAL library so can be easily used with CubeMX
2. Supports bitmap for generating images

**How to use**
1. Open CubeMX and set the clock to 168MHz
2. Go to Pinout Configuration Tab and Clear all Pins
3. In Connectivity Tab Enable I2C1 and set it to Fast Mode (Note This mode will not be available if the clock is not set in the previous step)
4. Connect the respective pins of OLED display to STM32F4 Board (SDA -- PB7 , SCL -- PB6).
5. Add the files in the respective folders (.h files in inc and .c files in src)
6. Include the file in the project using `#include "ssd1306.h"` and `#include "fonts.h"`

**Functions and their uses**
All functions and their uses are defined in the ssd1306.c file.

