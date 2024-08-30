# Stlink_stm32
using stm32 create stlink or stm32 debug another stm32 <br>
Source : http://slemi.info/2018/08/14/making-your-own-st-link-v2/ 


# How to use 
Flash Stlink.bin file into your stm32 then you can use it as a stlink , via this conect:
 - VCC (stm32=stlink) -> VCC (stm32- target)
 - Gnd (stm32=stlink) -> Gnd (stm32- target)
 - B12 , B14 (stm32=stlink) -> 220 ohm resistor -> SWDio (stm32- target)
 - B13 (stm32=stlink) -> 220 ohm resistor -> SWDio (stm32- target)

### *Note 
I use uart to flash firmware Stlink into stm32 , i will try stlink to see the result.

## Demo 




https://github.com/user-attachments/assets/dda744bc-70b9-473d-8dba-53ef92b061aa




