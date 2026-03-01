# XC8-18F25K22-Peripheral_Library

Repository with libraries for microcontroller peripherals. Each library has the ".c" and ".h" files with the name of the peripheral, It also has the functions to write an n number of bytes.

**List of peripherals:**
- ***eeprom:*** It contains the functions for writing and reading the internal EEPROM.
- ***INTERRUPTManager:*** This contains the functions to initialize and handle low and high priority interrupts.
- ***uart1:*** This contains the functions for writing and reading data through uart1 using interrupts. It is important to add INTERRUPManager to handle the Tx and Rx functions.

The content includes only the libraries; if you need an example of each one, I recommend checking my blog or consulting the example repository.

- ***Blog info:*** https://mrchunckuee.blogspot.com/2022/10/indice-pic18f25k22-con-xc8.html
- ***Examples repository:*** https://github.com/MrChunckuee-Electronics/PIC18F25K22-XC8_Examples


