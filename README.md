# ESP32_NeoPixel_Ring
## Description
This program uses an ESP32 microcontroller and a NeoPixel ring to display different colored lights based on an analog input signal.<br><b>2022</b>

## Hardware Required

- ESP32 board
- NeoPixel ring
- Potentiometer

## Instructions

1. Connect the ESP32 to your computer via USB.
2. Connect the potentiometer to analog input 4 of the ESP32.
3. Connect the NeoPixel ring to the ESP32's GPIO pin 15.
4. Upload the program to the ESP32 using the Arduino IDE.
5. Open the Serial Monitor to see debug output from the ESP32.
6. Turn the potentiometer knob to change the speed of the NeoPixel ring animation.

## Credits

This program is based on the [NeoPixel Ring simple sketch](https://github.com/adafruit/Adafruit_NeoPixel/blob/master/examples/strandtest/strandtest.ino) by Shae Erisson, released under the GPLv3 license. The program was modified to work with an ESP32 microcontroller and analog input. 

## License

This program is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

