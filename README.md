# EnvOpenPico
A RP2040 Based family of MCU boards

### Intentions

I orginally planed to make a RPI Pico clone with some personal improvements however Ive currently done that, I'd now like to make a few variations namely a DIP40 compatible version, and a full pinout version since the pi pico its self has a couple of un-used GPIOs.

I plan to make a few more varients namely one with some battery management and a version that allows wifi/bluetooth likely via SPI communication to a ESP-Pico-D4 or maybe if Raspberry Pi release another MCU with wifi/bluetooth capability that would be very nice.

### EnvOpenPico Notable Differneces
mainly Ive swapped out the Micro B port for a Type-C port, Its the Type-C-31-M-12 which I use on my keyboard PCBs and appears to stand up to quite a lot of heavy usage which I found you can wear out the port on the raspberry pi pico if you happen to use the same one a lot.

although the power management IC on the board will be changed due to stock issues, once stock problems are resolved Ill try to find a decently efficient buck-boost IC thats capable of hopefully 1.5A which is probably a bit overkill but we'll see.


### Notes
- You should be able to order these and have them entirely assembled by JLCPCB if they have stock
- If the pinout matches the Raspberry Pi Pico you should be able to use UF2s meant for the pico (i believe most RP2040 firmwares should be rather board agnostic but im unsure as of writing this)
- Please ensure you pick a compatible flash chip, you may need to modify the connections to the flash chip, its setup for Winbond W25QxxJVEIQ.

### Versions
- EnvOpenPico - This is the standard Raspberry Pi Pico clone that I've Made
- Dip40-RP2040 - This is a dip40 sized rp2040 board as this was a complaint I saw about the rpi pico.
- Dip40-RP2040-32A - This is another Dip40 rp2400 board but its meant to be pinout compatible with an Atmel ATmega32A.
- EnvOpenPico-Lipo - This version is the same as the standard pico clone except it uses a Battery/buck-boost IC meant to be used with Li-Po and Li-Ion batteries.

