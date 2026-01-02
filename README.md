# Lora
Lora devices project

The model I am going to use is Ebyte LoRa E22 400T30D

https://randomnerdtutorials.com/esp32-lora-rfm95-transceiver-arduino-ide/

## Tasmota 
You can use the Ebyte E22-400T30D with Tasmota, but not directly as a native Tasmota sensor or with standard "LoRa" commands. 
The E22-400T30D is a UART-based serial LoRa module based on the SX1268 chip. Tasmota's native LoRa drivers are designed for SPI-based modules (SX127x/SX126x). 
