## Getting started files

The following files are from the trivial example Blinky for OSHChip in the mbed environment

* OSHChip_Pin_Names.h
* OSHChip_Blinky.cpp
* OSHChip_Init.c

**OSHChip_Pin_Names.h** should probably be used in all OSHChip applications, regardless of the compiler environment

**OSHChip_Blinky.cpp** is a trivial program that uses OSHChip_Pin_Names.h and also shows the OSHChip_Init() function
being called at the beginning of main, to override the UART pin assignments that the mbed environment does prior
to main() being called.  In non-mbed environments, the UART setup is more complex. Until I write an OSHChip specific
version, please refer to Nordic's SDK.

**OSHChip_Init.c** While this function is specific to the mbed environment that sets up the UART before main() is called, the techniques used to assign UART pins and change the BAUD of the UART are applicable for all compiler environments.
