# XIAO ESP32 S3 Breakout Board

This board is designed to break out the PWM control wires from the Seeed Studio XIAO ESP32 S3 microcontroller to two RJ45 ports. There is also a place to connect a passive (or active) buzzer for amazing sound effects.

## Components
### Microcontroller:
- 1x Seeed Studio XIAO ESP32 S3
### RJ45 Ports:
- 2x 855055113 (2 positions available on board)
### Buzzer (OPTIONAL):
- 1x Passive or Active buzzer 12x9.5RM7.6 (the super common ones you see in Arduino kits)

## Diagram
<img width="1041" height="1043" alt="image" src="https://github.com/user-attachments/assets/680703d1-ce05-4d54-8a2e-ab24b750bf94" />

## Pins and Peripherals
As seen in the diagram above, GPIO 1-8 are used for motor PWM control. GPIO 9 is used for the analog source for the buzzer.

This schematic is designed around the LEDC peripherals and library on the microcontroller. 

DO NOT use the servo libraries, because it often defaults to the motor control peripherals, limiting the output to only a couple of PWM signals rather than 8!

## Plans
- Potentially make this just incorporated onto the ESC board so that we dont have long ethernet cables.

## Contact
For any questions, feel free to message me via my number or send me an email:- (586) 255-5422 kchirco@umich.edu
