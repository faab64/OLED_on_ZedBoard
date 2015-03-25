# OLED_on_ZedBoard
OLED test code from Digilink modified to work on the Zedboard

This is to show how you can use the OLED module on the Zedboard form the FPGA side.

If you want to use the OLED via the ARM core, you need to add a SPI controller to the system

1- add GPIO peripherals;
2- click YES; add IP;
3- the channel1 bit width is set to 2; other default; click OK;
4- SPI interface to connect peripheral options, will not have a broken signal lines;

After that, you need to write a C code to set up and access the device. 
I do not have this available at the moment, but will put it here when I find it together with some example code on how to use it.

