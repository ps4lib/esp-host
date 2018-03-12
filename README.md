# esp-host

![alt tag](https://raw.githubusercontent.com/Codworth/esp-host/master/esp8266.jpg)


Benefits of using the ESP8266

    -very simple procedure, just flash the included .bin and connect to the wifi network.
    -extremely low cost hardware , available worldwide 
    -completely block all possibility of firmware updates
    -ability to run 24/7 via usb, self-hosted payload, no external apps or programs required.
    -no need to edit dns servers or settings, features automatic redirect.
    -easy updates via usb
    -very low power consumption


Requirements:

    -esptool.py or other suitable esp8266 flashing tool (many available)
    -ESP8266 Wifi Module with at least 4M flash 
    -Firmware 4.55




Instructions:
    -flash the ESP8366 using the following command:

    sudo esptool.py --port /dev/ttyUSB0 write_flash 0x00000 0x400000 ./esphost.bin
    
    -after flashing completes, connect to "PS4-WIFI" using "easy setting"  then launch payload as normal.
    
    -NOTE: windows users must use the appropraite com port when flashing with esptool.py
    
    
    
Compataible boards:

These are the most popluar esp8266 boards, but any esp8266 with 4M flash or larger will work.

    ESP8266 NodeMcuV2 4M wifi Module        (amazon) https://tinyurl.com/y9xskhcy
    			                (aliexpress) https://tinyurl.com/y7jq3fnq
                                
   ![alt tag](https://images-na.ssl-images-amazon.com/images/I/51XTrgJ-HLL._SL500_AC_SS350_.jpg)
   
                                     
    ESP8266 D1 Mini NodeMcu 4M              (amazon) https://tinyurl.com/y9mx83ev
                                            (aliexpress)https://tinyurl.com/y8rqfafz
   ![alt tag](https://images-na.ssl-images-amazon.com/images/I/71EzBFuoVqL._SY355_.jpg)
                               
                               

