# The Firmware for OSHChip_CMSIS_DAP

The Firmware is described here <a href="https://developer.mbed.org/handbook/cmsis-dap-interface-firmware" target="_blank">mbed HDK Firmware</a>

The firmware described can be used with several different microprocessors
which can be seen here <a href="https://github.com/mbedmicro/CMSIS-DAP/tree/master/interface/mdk" target="_blank">Microprocessors</a>

OSHChip_CMSIS_DAP V1.0 uses the NXP LPC11U35 microprocessor.
The above firmware is quite dated and does not describe the nRF51822 target CPU
that is used in OSHChip V1.0. A branch of this firmware with support
for nRF51822 has been developed by Yihui Xiong of Seeed Studio.
This version of the firmware is also used by OSHChip_CMSIS_DAP V1.0.

It is here: <a href="https://github.com/xiongyihui/CMSIS-DAP" target="_blank">Firmware Supporting nRF51822</a>

For OSHChip_CMSIS_DAP, only very minor cosmetic changes were made to the firmware to acknowledge its origin.

There are two versions, that differ only in the default drive name that shows up in your operating system's file explorer

