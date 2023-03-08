# STM32-Serial-to-Ethernet-Converter
 
 STM32 board to be used for conversion between serial protocols to ethernet. It has 3V3 RS232 with DB-9 connector, 3V3 RS485, 5V CAN and ethernet. For ethernet connection WIZnet W5500 ethernet controller has been used.
 
 - RS232 connected to USART1 perihperal.
 
 - RS485 connected to USART2 peripheral.
 
 - CAN bus connected to CAN peripheral.
 
 - W5500(for ethernet) SPI interface connected to SPI1 peripheral.
 
 - SWD pins broken out for configuration and debuging.
 
 Stack up is 4 layers which is
 
 ---Signal
 
 ---Ground
 
 ---Ground
 
 ---Signal/Power
 


![STM32_S2E_Top](https://user-images.githubusercontent.com/79105578/223508234-4ef781dd-2139-4ef8-bb6c-746924066e7d.PNG)

![STM32_S2E_Bottom](https://user-images.githubusercontent.com/79105578/223508257-885399f1-9306-4c0c-a47b-ce05430a14d8.PNG)

![STM32_S2E_3D1](https://user-images.githubusercontent.com/79105578/223508282-88e48142-0bb5-47c6-b90f-895569df1125.PNG)

![STM32_S2E_3D2](https://user-images.githubusercontent.com/79105578/223508300-85be2c28-1d2b-4749-be9d-3017898f8e57.PNG)

![peripherals](https://user-images.githubusercontent.com/79105578/223512130-017878ea-c81b-477e-8c44-21316f451da6.PNG)

