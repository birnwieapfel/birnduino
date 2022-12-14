# birnduino
An Arduino clone with an RS232 serial interface.

In 2013, I bought a board call "Freeduino Serial v2.0", which is an Arduino clone having an RS232 serial interface using a MAX232. But it seems that it is not available anymore now and I could not find the original files of the "v2.0". So I decided to create my own based on some information about the Freeduino I found in the internet and having a look at my "Freeduino Serial v2.0" board...

## Repository content
- The [inputs folder](inputs) contains the resources which helped me to create the schematic and PCB
- The [datasheets folder](datasheets) contains the datasheets for the used ICs
- The KiCad 6.0 files for the schematic and PCB are in the [KiCad subfolder](KiCad)
- *to come...* Image(s) of the PCB can be found in the folder *images*

## Old resouces
Here are some links which helped to realize this project:
- https://thdarduino.blogspot.com/2015/12/freeduino-serial-v20-bausatz.html

## Other links
- https://freeduino.org/freeduino_open_designs-html
- https://github.com/WestfW/Freeduino-historical

## License
Copyright 2022, Robert Birn. All Rights Reserved.

"birnduino" is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode) by Robert Birn.

This work, "birnduino", is a derivative of "Freeduino Serial" by CircuitJoy and Spiffed, released under CC BY-SA 2.5. 

"Freeduino Serial" is based on the Arduino Diecimila reference design (www.arduino.cc/main/ArduinoBoardDiecimila).

I started the work by using the **Arduino KiCad Library**, available here: https://github.com/Alarm-Siren/arduino-kicad-library. Remark: After an update, no reference to this library is existing anymore.
