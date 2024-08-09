# EnvOpenPico
A RP2040 Based family of MCU boards

### Intentions and Info
The intentions of this project were mainly to learn about MCU design and also to make a rpi pico like device using a RP2040 that has some improvements or changes that you'd find useful, so far Ive changed the type-c port and added a reset button as well as replaced the buck boost IC with a linear regulator which doesnt generate the same switching noise which makes it good for audio.

Ive retained the USB TP pads and also TP6 which is bootsel in their original positions.
a couple of the GPIOs cant retain their original function since Im not using a RT6150B-33GQW so GPIO23 has an optional mosfet for a default on LED instead of controlling the mode for the buck-boost IC.

Ive also got nothing connected on GPIO29 where as the pico has a mosfet to prevent leakage current, im not sure what the use of this GPIO is but if its a wanted feature I can try to add it back.

Update: 09th Aug 2024 - Raspberry pi has released the RP235XA and RP235XB, I have started work on making variants of the main Pico board to fit the RP2350 and RP2354.

### Permissions
You have my permission to fork and learn from this design for your own projects including if you wish to sell those on as a product. 

### Important!!
I have only had the EnvOpenPico made so the other variants like the PicoLipo and the EliteMicro2040 I cant fully confirm if the design works but since its all derived from the main project I should hope it all works as intended.

### Notes
- You should be able to order these and have them entirely assembled by other PCBA suppliers if they have stock of all the parts, ive made sure to label everything in the schematic properly.
- Please ensure you pick a compatible flash chip, you may need to modify the connections to the flash chip, its setup for Winbond W25QxxJVxxx.


### Other
If you want to see pictures of the main PCB you can check out the _photos folder

PCBway kindly sponsored a batch of PCBs which you can see pictures of inside the _photos folder.
![pcbway logo](_photos/PCBwaylogo.png)
http://pcbway.com