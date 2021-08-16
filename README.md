# MyAVR-Core
Arduino support for the MyAVR boards and programmers.
If you are interested in the MyAVR boards and programmers, please visit the website https://shop.myavr.com/
this repostiory is not created/maintained by the Sisy solutions company. please buy their products from the website.

## supported Boards
currently these boards are included:
- MyAVR board MK2

## supported Programmers
currently these programmers are included:
- MySmartUSB MK2 (programmer and bridge)

More information about the boards and programmers can be found at https://shop.myavr.com/

## Installation
to install the MyAVR-Core, add the json file to your additional boards manager url in the preferences of arduino
https://pgosliga.github.io/MyAVR-Core/MyAVR-Core.json


## Boards
### MyAVR MK2 V2.10
![Image of MyAVR MK2](https://pgosliga.github.io/MyAVR-Core/images/MyAVR_Board-MK2-Top.png)

#### pinout layout
| Arduino |    0|    1|    2|    3|    4|    5|    6|    7|    8|    9|   10|   11|   12|   13|   A0|   A1|   A2|   A3|   A4|   A5|
|:---:    |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|     AVR |   D0|   D1|   D2|   D3|   D4|   D5|   D6|   D7|   B0|   B1|   B2|   B3|   B4|   B5|   C0|   C1|   C2|   C3|   C4|   C5|
|Function |  RXD|  TXD|     |  PWM|     |  PWM|  PWM|     |     |  PWM|  PWM|  PWM| MISO|  SCK|     |     |     |     |  SDA|  SCL|


