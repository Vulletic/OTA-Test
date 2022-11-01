# OTA-Test
This repository is use for OTA functionality in the dispenser device.

## How it works?
There are two important files in the repository. 

### firmware.bin file
This is the binary file generated by the compiler when we build the proyect. You can find this file in the following path:
´´´
Dispensador-Dispositivo\Prototipo\FirmwareEsp32\.pio\build\esp32dev\firmware.bin
´´´
### version.txt file
This file contains the serial numbers of the devices **you want to update**.

**Important**: The file has the following format
**[serialnumber][,][SPACE][serialnumber][,][SPACE][serialnumber]** 
For example:
1001, 1002, 1003, 1004
