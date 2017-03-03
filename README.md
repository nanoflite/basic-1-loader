# BASIC-1 loader

With this tool I program my BASIC-1 computer from my macbook.

The keyboard is driven by an Arduino mini and provides serial output to the XMEGA running BASIC.

I connected an audio switch jack between the Arduino Mini and the XMEGA. When I plugin the audio jack, the connection to the Arduino is broken and I can use a USB to UART cable connecte dto the jack to take over the BASIC-1 keyboard.

```
                ---------- USB to UART
               /
XMEGA ---(switch jack)
               \
                ---------- Arduino Mini C64 Keyboard driver
```
