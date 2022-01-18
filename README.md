# CH330_Hardware USB-UART Converter

I created this board because I wanted to play with the CH330N because it was supposed to be a crystal-less, <$0.35 USB UART converter in a SOIC-8 package. Since these chips were available from LCSC, I created a quick design and ordered both together.

As the IC is very small (other USB UART converters are packed in at least a QFN or SOIC-16), I didn't want the board to get much bigger. Accordingly, I developed this 10*10mm USB UART converter board with the CH330N and micro-USB. The assembly is quite fiddly, I suggest that you reflow the USB port and then solder the CH330N (and the LEDs) by hand. If you want to order these boards, I recommend you panelize them.

The CH330N enumerates as CH340 or CH341 and its transfer speed goes up to ~2Mb/s.

#### [More Info (Twitter Link)](https://twitter.com/_Jana_Marie/status/1057014341155872769)
#### [This project on Kitspace.org](https://kitspace.org/boards/github.com/jan--henrik/ch330_hardware/)

### Images

![H1](https://pbs.twimg.com/media/DsmIqXtXoAIwU_J.jpg)
![H2](https://pbs.twimg.com/media/DsmIrubWwAIRDZC.jpg)
![Front](/images/front.png)
![Back](/images/back.png)
