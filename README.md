# e-Paper  
waveshare electronics
![waveshare_logo.png](waveshare_logo.png)

## 中文:  
Jetson Nano、Raspberry Pi、Arduino、STM32例程
* RaspberryPi_JetsonNano  
    > C
    > Python 
* Arduino:  
    > Arduino UNO  
* STM32:  
    > STM32F103ZET6 
    
更多资料请在官网上搜索:  
http://www.waveshare.net


## English:  
Jetson Nano、Raspberry Pi、Arduino、STM32 Demo:  
* RaspberryPi_JetsonNano:  
    > C
    > Python
* Arduino:  
    > Arduino UNO  
* STM32:  
    > STM32F103ZET6 
    
For more information, please search on the official website:   
https://www.waveshare.com

## Modifications for OrangePi i96
updated e-Paper/RaspberryPi_JetsonNano/python/lib/waveshare_epd/epdconfig.py to work with OrangePi i96

Connections for my 1.54 inch e-paper display:

| E-Paper | i96 | Pin Number |
|--- |--- |--- |
| VCC  | V_PAD    | 35 |
| GND  | GND      | 40 |
| DIN  | SPI2_DO  | 14 |
| CLK  | SPI2_CLK | 8  |
| CS   | A15      | 23 |
| DC   | A20      | 24 |
| RST  | A30      | 29 |
| BUSY | A29      | 30 |




