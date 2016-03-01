# Example_Hex_Files
Some example hex files to do basic test of OSHChip and the programmer

* **OSHChip_V1_0_Test.hex**  
  This is the program that OSHChip_V1.0 is shipped with. It does a simple test of all the pins
  on the device and blinks the LEDs. It blinks each LED once in the sequence Red, Green, Blue,
  then blinks Blue for each phase of the test program. It then repeats. The program assumes
  that OSHChip is not plugged into anything, not even the anti-static foam (it is conductive).
  If it blinks Red continuously, it has detected a problem.
* **Test_tripple_blink.hex**  
  Every OSHChip_V1.0 is also tested with this program, just to prove that one program can be
  overwritten by another by the programmer. It blinks each LED once, then uses a PWM function
  to fade all 3 LEDs together on and off 5 times.
* **OSHChip_Pin_Names.h**  
  Well, this is not a hex file, but it is fairly useful. This file contains all the #defines
  that map the I/O port bits inside the chip to the 14 physical pins on the OSHChip package.
  
