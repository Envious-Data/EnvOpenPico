# EnvOpenPico
A Raspberry Pi Pico Clone which also uses the RP2040.

![Board image](EnvOpenPico.jpg)

### Info
I originally made this as I wanted to replace my raspberry pi pico with a version that had Type-C because I didnt like how the Micro Type-B ports on mine were wearing out already.

Ive tried to keep the pinout the same as the pico however ADC VREF and AGND I couldnt get to work how I wanted in kicad nor could I properly figure out how to replicate it correctly so Ive replaced ADC VREF with another ADC GPIO and AGND is just a normal GND which is the same as all other GND pins on the board.