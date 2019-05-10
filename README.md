# Four Digit Display (TM1637)
makecode Four Digit Display (TM1637) Package for microbit  

LED Digit Display Module with 1-6 (normal four) 7-segment LED, it can show number. It has TM1637 chip inside, control with a 2-wire interface.  

![](https://github.com/DoraLC/pxt-TM1637/blob/master/4-LED.jpg)

## API

- **create(clk: DigitalPin, dio: DigitalPin, intensity: number, count: number)**  
create a TM1637 object.  
  - clk, any DigitalPin  
  - dio, any DigitalPin  
  - intensity, set display brightness, range [0-8]  
  - count, LED count, range [1-5]  

- **on()**  
turn on the display.  

- **off()**  
turn off the display.  

- **clear()**  
clear content of the display.  

- **showbit(num: number, bit: number)**  
show a digit number in given position.  

- **showNumber(num: number)**  
show a interger number in display.  

- **showHex(num: number)**  
show a hex number.  

- **showDP(bit: number, show: boolean)**  
show or hide dot piont in give bit  
bit is dot piont position, [0 - count]  
show, True will show DP, other will hide it  

- **intensity(dat: number)**  
set display intensity.  

## License  

MIT

Copyright (c) 2018, microbit/micropython Chinese community  

## Supported targets  

* for PXT/microbit