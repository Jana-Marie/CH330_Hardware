# CH330_Hardware

I made this board because I wanted to play with the CH330N, which is supposed to be a crystalles, <0.35$ USB-UART converter in a SOIC-8 package. As these chips where avaiable at LCSC, I made a quick 
design and ordered them together.

As the IC is realtivly small (other USB-UART converters aer packed at least in a QFN or SOIC-16) I didn't want the board to be much larger in size. Accordingly I created this 10*10mm USB-UART converter 
with the CH330N and micro-USB. The assembly is quite fiddly, I suggest you to reflow the USB-connector and then solder the CH330N (and the LEDs) by hand. Also if you want to order those PCBs, I suggest 
you to panelize them.

The CH330N enumerates as CH340 or CH341 and its transmission speed goes up to ~2Mb/s.

[More Info](https://twitter.com/JanHenrikH/status/1057014341155872769)

![Front](https://raw.githubusercontent.com/Jan--Henrik/CH330_Hardware/master/images/front.png)
![Back](https://raw.githubusercontent.com/Jan--Henrik/CH330_Hardware/master/images/back.png)
