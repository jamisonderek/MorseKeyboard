# MorseKeyboard
Convert morse code into HID keyboard input

# Details
This is for an Arduino Leonardo or similar, which supports the keyboard.h header file.
You connect a switch between pins 10 and pin A0.
A short press of the switch will send a ".", while a long press will send a "-".
A really long press will do a backspace.

Once you have completed sending a letter, it will backspace and replace with the correct letter.

# Background
I originally wrote this when my son showed me a video, but it turned out it was an iFunny joke.
Here is my demo [video](https://youtu.be/t0_WnyZHLvk).

# Parts
Here are my Amazon affiliate links to the part I used in the video.
If you purchase via this link, I may earn a commission.
- https://amzn.to/3S7bjGj

The original part I used is out of stock, but it looks like this is very similar:
- https://amzn.to/3I2wYuy

The other option is to use a Attiny85 and then follow the directions to use a [digitspark module]
(https://maker.pro/arduino/projects/how-to-build-a-rubber-ducky-usb-with-arduino-using-a-digispark-module).
You would need to modify the code to use "DigiKeyboard.h" and "DigiKeyboard.sendKeyStroke" &
"DigiKeyboard.print" -- but it should be very possible.
- https://amzn.to/3E8BHtG