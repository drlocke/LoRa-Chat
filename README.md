# LoRa-Chat

Arduino chat code for LoRa WAN modules running in serial bidirectional send/receive mode (input via console).

Built from the duplex example of https://github.com/sandeepmistry/arduino-LoRa .

Credits goes to https://github.com/sandeepmistry .

## Pinout

<p align="center"><img src ="https://i1.wp.com/randomnerdtutorials.com/wp-content/uploads/2018/08/ESP32-DOIT-DEVKIT-V1-Board-Pinout-36-GPIOs-updated.jpg?w=750&ssl=1"></img></p>

## Pinmap

__***ESP32***__  
SCK  -> 18  
MISO -> 19  
MOSI -> 23  
SS   -> 5  
  
__***LORA***__  
SS_LORA   -> 5  
RST_LORA  -> 16  
DIO0_LORA -> 2  

## References

&emsp;***[1]*** [*Banggood homepage*](https://www.banggood.com/ESP32-Development-Board-WiFibluetooth-Ultra-Low-Power-Consumption-Dual-Cores-ESP-32-ESP-32S-Board-p-1109512.html)  
&emsp;***[2]*** *Lora WAN example on* [*github*](https://github.com/sandeepmistry/arduino-LoRa)  
&emsp;***[3]*** *Installing Arduino IDE on* [*Windows*](https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/)  
