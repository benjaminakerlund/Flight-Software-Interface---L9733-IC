# Flight-Software-Interface---L9733-IC
Assignment for job application to Flight Software Engineering July of 2021. 

The assignment was to propose an interface for a driver of L9733 integrated circuit, in form of a C header file.

* No actual implementation of the driver is needed. Write just the header file. The header should contain function prototypes and whatever other items you consider necessary to interact with the chip.
* Write a C language header; assume the compiler can handle C99 standard. Don't use C++.
* Assume the driver will be used on 32-bit microcontrollers, in bare-metal and RTOS applications.
* Strive for "flight grade" quality of your design and code. Assume it is intended to actually fly on a spacecraft. 
* If you need it, you can assume there is a spi.hheader available, and it contains a spi_ttype,
which represents the SPI controller of the MCU, and allows you to perform operations on it. If you need any symbol names from spi.h(functions, types, constants) just invent them.
* We will not use your code in any actual application. Anything you write will be used solely for the purpose of the recruiting process.
* Assume that somebody else will use your header file to write different applications. Add comments to your code to guide the application writer on how to use your data structures and functions. If you have special remarks about the limitations of your interfaces, add them into the comments too.
