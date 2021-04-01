# yarh.io-mods
MODs for
[Y]ET [A]NOTHER [R]ASPBERRY [H]ANDHELD

original idea and files can be found here

https://yarh.io/yarh-io-mki.html

![Assembly](https://user-images.githubusercontent.com/10408121/113345382-a8870180-9332-11eb-8fce-94cc96dc7f78.png)


i added 5 programable GPIO buttons to the front and a custom made pcb (see kicad files) 
to connect the buttons and the RTC (or any other i2c device for that matter)
it can be hooked up to the free pinheader at the back of the LCD...

i uploded modified stl files for the frontpanel.
i also closed a few holes i didnt utilize and simplified the cabeling for my purpose.
and added a camera holder to the housing. for my purpose for a purethermal2 FLIR camera,

the additional parts i used

Prototype PCBs:

AZDelivery Set 16 x PCB Board
AZ-Delivery Vertriebs GmbH
https://www.amazon.de/dp/B078HV79XX/ref=cm_sw_em_r_mt_dp_2RHM7PPPENVQ2NX6XCZS?_encoding=UTF8&psc=1
or
ELEGOO Prototyp-Kit for DIY
ELEGOO Official US
https://www.amazon.com/dp/B072Z7Y19F/ref=cm_sw_em_r_mt_dp_VJY9EARDYE1PZMNZ06P7?_encoding=UTF8&psc=1

------------------------------------------------------------
Buttons:

YIXISI 180 pcs Button Micro Tactile Switch (4 pin 6x6mm 7x7mm)
YXS-DE
https://www.amazon.de/dp/B082ZL867J/ref=cm_sw_em_r_mt_dp_96NSV17K3W1S4MMYA5SG?_encoding=UTF8&psc=1
or
4 Pin Momentary Push Button Switch Sortiment Kit
BOJACK ELECTRON
Erfahren Sie mehr: https://www.amazon.com/dp/B07ZBHXBZ4/ref=cm_sw_em_r_mt_dp_M1YMZXK227A3NDJCXFJZ

------------------------------------------------------------

further information:

how to programm a shutdown button:
https://www.stderr.nl/Blog/Hardware/RaspberryPi/PowerButton.html

setting up gpio buttons via device tree overly (dtoverlay):
https://blog.gegg.us/2017/01/setting-up-a-gpio-button-keyboard-on-a-raspberry-pi/

enabling hwclock and deleting fake-hwclock:
https://pimylifeup.com/raspberry-pi-rtc/
