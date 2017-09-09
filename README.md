## Arduino Ciao (MCU side)
Simple library in C to make MCU communicate with "outside World" through Ciao Core.

### What is Arduino Ciao?

**Arduino Ciao** is a easy-to-use and powerful technology that enables Arduino sketches to communicate intuitively with the "outside World". It aims to simplify interaction between microcontroller and Linino OS allowing a variety of connections with most common protocols, third-party services and social networks.

Arduino Ciao is open-source and distributed under MIT license: feel free to read it, suggest improvements, provide feedbacks and develop new features.

More information about Arduino Ciao project can be found at http://labs.arduino.org/Ciao

### Arduino Ciao (MCU side) - Ciao Library

Arduino Ciao is made of two main parts:
 * the **Ciao Library** - usable inside *sketches*, it's written in C.
 * the [Ciao Core](http://labs.arduino.org/Ciao+CPU) - a library developed in python that runs on the CPU/MIPS side of the board.(source code available [here](https://github.com/arduino-org/Ciao))

**Ciao Library**  allows you to send and receive data outside the microcontroller, through a serial communication, in a simple and intuitive way.

Details about **Ciao Library** architecture are available in the [Arduino wiki](http://labs.arduino.org/Ciao+MCU)
