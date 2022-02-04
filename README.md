# Eurorack-PCB
This project is pcb for eurorack device.<br />
![image](https://user-images.githubusercontent.com/98973485/152459374-d280f996-794a-41e8-bf27-694d0db06bff.png)

## Overall
The aim of this project is design new module of Eurorack and write firmware
Above picture is frontpanel of Eurorack…
It includes LCD, Rotary Encoder, Jack Input, Jack Output, LEDs.. 

-	LCD:	16 x 2 LCD <br />
![image](https://user-images.githubusercontent.com/98973485/152459499-439f88c7-be1a-47dc-b3cc-d253e8a545f4.png)
<br />
It has 2 rows. Every pin’s function is like this.<br />
![image](https://user-images.githubusercontent.com/98973485/152459957-ef05566c-3bad-4b55-99cf-35cde26c5a7e.png)
<br />

-	Rotary <br />
![image](https://user-images.githubusercontent.com/98973485/152459976-278c97cc-b4c4-4b92-8691-39617911a35b.png) 

-	LED <br />
-	JACK Input/Output <br />
Input: 	8 port
Output:	8 port
-	SDCARD

## Specification
-	MCU:	STM32F405
-	Audio:
o	Clock :	500BPM
o	Frequency:	44.1KHz
o	Resolution: 24Hz
-	Size: 6 cm x 40cm (front panel)
-	LCD Interface: parallel
-	Flash(or EEPROM)

## Plan
-	First: Make schematic and PCB layout..<br />
The result will be like this. <br />
![image](https://user-images.githubusercontent.com/98973485/152460062-f423f50d-4e19-42a7-921c-8d76e6c41e8b.png)

-	Second: Write firmware<br />

STM32F405RG’s specification:<br />
1MB flash<br />
168MHZ clock<br />
SPI, I2C, UART, 12bit ADC/DAC, etc..<br />
Like this:<br />
![image](https://user-images.githubusercontent.com/98973485/152460081-890d7e0f-6bce-404a-9733-7247f379f56a.png)
![image](https://user-images.githubusercontent.com/98973485/152460087-eab49645-7c06-4310-9006-f7c5a37a6311.png)

 
 
