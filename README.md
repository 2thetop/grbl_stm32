# GRBL for STM32 - NUCLEO

This repo represents the version of GRBL for [STM32F411RET6][MCU_LINK] MCU. This MCU is located on the [STM NUCLEO][BOARD_LINK] board, picture 1.1. This project can be used with standard GRBL shield like [Arduino CNC Shield][ARDUINO_SHIELD_LINK] or three STM shields [
X-NUCLEO-IHM01A1][STM_SHIELD_LINK], for stepper motors. With minor modifications [COREXY][COREXY_LINK] configuration is also supported.

![alt tag][NUCLEO_PICTURE]

### Why NUCLEO board?

Reasons for choosing open Nucleo environment are:
- it is cheaper then Arduino UNO
- better ARM MCU, a possibility for new features
- open SDK and IDE

### Documentation
All documentation on this project, how to compile code, and what to change for different hardware setups, can be found on project [Wiki][WIKI_LINK] 

### Diferent versions
This project can be used with diferente hardware setings. Here are presented several versions with compiled **.elf** files just to download to the Nucleo board.

##### 1. NUCLEO STM + 3x ST Stepper drivers
  Hardware:
 - [NUCLEO-F411RE][BOARD_LINK]
 - 3x [X-NUCLEO-IHM01A1][STM_SHIELD_LINK]

Binary: download here

##### 2. NUCLEO STM + GRBL shield
  Hardware:
 - [NUCLEO-F411RE][BOARD_LINK]
 - [Arduino CNC Shield][ARDUINO_SHIELD_LINK]

Binary: download here

##### 3. NUCLEO STM + GRBL shield (COREXY)
  Hardware:
 - [NUCLEO-F411RE][BOARD_LINK]
 - [Arduino CNC Shield][ARDUINO_SHIELD_LINK]
 - [PreciseXY][PRECISEXY_LINK]

Binary: download here

### Version
1.0.0



[//]: # (These are reference links used in the body)

   [BOARD_LINK]: <http://www.st.com/web/catalog/tools/FM116/SC959/SS1532/LN1847/PF260320#>
   [MCU_LINK]: <http://www.st.com/web/catalog/mmc/FM141/SC1169/SS1577/LN1877/PF260049>
   [NUCLEO_PICTURE]: <http://www.st.com/st-web-ui/static/active/en/fragment/product_related/rpn_information/board_photo/nucleo-F4.jpg>
   [ARDUINO_SHIELD_LINK]: <http://blog.protoneer.co.nz/arduino-cnc-shield/>
   [STM_SHIELD_LINK]: <http://www.st.com/web/en/catalog/tools/FM116/SC1077/PF260715>
   [COREXY_LINK]: <http://corexy.com/>
   [PRECISEXY_LINK]: <https://github.com/IRNAS/PreciseXY>
   [WIKI_LINK]: <https://github.com/IRNAS/grbl_stm32/wiki>
   
