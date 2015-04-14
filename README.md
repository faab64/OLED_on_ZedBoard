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

For those of you who want to know more about the OLED module on the board, you can find the datasheet of the device on:
       http://www.adafruit.com/datasheets/UG-2832HSWEG04.pdf

IF you want to use the OLED from the ARM side of the Zynq device, you can either use the guide on this page:

      http://stackoverflow.com/questions/29322127/oled-on-zedboard/29322422


If you want to access the OLED from the CPU side, maybe this page:

      http://www.themakersworkbench.com/Digilent%20Pmod%20OLED%20Review

Can help you to find a way to communicate with the OLED device on the Zedboard.

At the moment, I am really busy, but maybe one day, I make a project in Vivado and put it on the side of this project and write a short document on how to use it, but for now, I am afraid this is all I can provide.
