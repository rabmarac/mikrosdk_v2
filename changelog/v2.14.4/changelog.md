<p align="center">
  <img src="http://www.mikroe.com/img/designs/beta/logo_small.png?raw=true" alt="MikroElektronika"/>
</p>

---

**[BACK TO MAIN FILE](../../changelog.md)**

---

# `v2.14.4`

+ released: 2025-05-15

## Changes

+ [`v2.14.4`](#v2144)
  + [Changes](#changes)
    + [New features](#new-features)
      + [mikroSDK](#mikrosdk)
    + [Fixes](#fixes)
      + [mikroSDK](#mikrosdk-1)
      + [CORE](#core)
    + [NEW HARDWARE](#new-hardware)

### New features

#### mikroSDK

+ Added variations of the standard C `sprintf` function:
  + `sprintf_me()`
    + Full implementation supporting integers, floats, characters, and strings
    + Used to format and store detailed strings from various data types
  + `sprintl_me()`
    + Extended version of `sprinti_me()` supporting long decimal values
    + Useful for creating strings that include large numeric values
  + `sprinti_me()`
    + Lightweight version for basic types (integers, characters, strings), optimized for minimal code size in embedded systems
    + Ideal for embedded systems needing minimal memory usage
  + These functions are used to convert values (like numbers or characters) into a formatted string — similar to the standard
    C sprintf, but tailored for embedded systems

### Fixes

#### mikroSDK

+ Updated UART logger
  + Improved error handling during UART module initialization
  + Configured macros for pin mapping and additional options to use interrupt mode by default
+ Fixed the TFT_BPWM pin for boards EasyPIC PRO v8 and EasyAVR PRO v8
+ Fixes for PIC18FxxQ8x MCUs
  + Corrected certain register addresses, resolving I2C communication issues
  + Updated relevant regex patterns to ensure compatibility with *mikroC AI for PIC*
+ Fixed clock setting for USB in tinyUSB implementation for STM32L4
    + For STM32L47x/L48x clock source for USB should be set to PLLQ

#### CORE

+ Fixed USB clock schemes for STM32L47x/L48x

### NEW HARDWARE

> NOTE:
>> If any new hardware was added to current version, it will be listed here.

Support added for following hardware:

+ **[2025-05-15](./new_hw/2025-05-15.md)**
+ **[2025-05-16](./new_hw/2025-05-16.md)**
+ **[2025-05-19](./new_hw/2025-05-19.md)**
+ **[2025-05-20](./new_hw/2025-05-20.md)**
+ **[2025-05-21](./new_hw/2025-05-21.md)**
+ **[2025-05-22](./new_hw/2025-05-22.md)**
+ **[2025-05-23](./new_hw/2025-05-23.md)**
+ **[2025-05-26](./new_hw/2025-05-26.md)**
+ **[2025-06-03](./new_hw/2025-06-03.md)**
+ **[2025-06-04](./new_hw/2025-06-04.md)**
+ **[2025-06-05](./new_hw/2025-06-05.md)**
+ **[2025-06-06](./new_hw/2025-06-06.md)**
+ **[2025-06-09](./new_hw/2025-06-09.md)**
+ **[2025-06-10](./new_hw/2025-06-10.md)**
+ **[2025-06-11](./new_hw/2025-06-11.md)**
+ **[2025-06-12](./new_hw/2025-06-12.md)**
+ **[2025-06-13](./new_hw/2025-06-13.md)**
+ **[2025-06-16](./new_hw/2025-06-16.md)**

---

**[BACK TO MAIN FILE](../../changelog.md)**

---
