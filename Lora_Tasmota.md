This project is to connect Lora with Tasmota for easy configuration.
This project will use the following items
For the Tranmitting and Receiving parts.
1. ESP8266
2. Arduino Pro Mini (5 V) 
3. Ebyte LoRa E22 400T30D
4. 3.3 V regulator  
5. 220 VAC to 5V regulator

Project Descriptions
ESP8266 will connect to Arduino Pro Mini with a Serial communition (Client TX, Client RX and Client RST) 
The following is the pin connection of the two devices

ESP	Arduino Pro Mini (3.3V)
VCC	VCC
GND	GND
D2 (GPIO4)	RX (0)
D1 (GPIO5)	TX (1)
D4 (GPIO2)	Reset (RST)

![image](https://user-images.githubusercontent.com/16104631/219649515-b61a0874-ce58-4d22-b88a-9c6216a9d178.png)

Ref:https://tasmota.github.io/docs/TasmotaClient/#getting-things-wired-up

In my case, I will use ESP 8266 without 3.3 V regulator onboard. I will use external 5V to 3.3 V regulator
because Ebyte LoRa E22 400T30D also needs 3.3 V input.
