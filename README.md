# arduino_installation_under_linux
This repository contains the notes about how to download ans install arduino IDE under linux.

1. Download the Arduino IDE AppImage
Go to the [official arduino website](https://www.arduino.cc/en/software) to download Arduino IDE. I chose **Arduino IDE 2.2.1**, just download the AppImage by clicking on "Linux AppImage 64 bits (X86-64)". 



2. Make the AppImage executable
By default, the AppImage is not executable, to make it executable you need to run:
```
chmod +x arduino-ide_2.2.1_Linux_64bit.AppImage
```

3. Launch Arduino IDE
To launch the Arduino IDE, simply by entering in your terminal:
```
./arduino-ide_2.2.1_Linux_64bit.AppImage
```
