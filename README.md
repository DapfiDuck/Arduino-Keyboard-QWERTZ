# Keyboard library for qwertz keyboards

## Description
The keyboard functions enable 32u4 or SAMD micro based boards to send keystrokes to an attached computer through their micro’s native USB port.

**Note** Not every possible ASCII character, particularly the non-printing ones, can be sent with the Keyboard library.
The library supports the use of modifier keys. Modifier keys change the behavior of another key when pressed simultaneously.

This fork aims at modifying the keyboard.ccp and the keyboard.h in a way that an arduino running it can be connected to a machine running a qwertz Keyboard. Not all keys have been corrected at this point in time.

***

## Installation 

Clone this Library onto your machine. Now find the installation Foulder of Arduino, and goto libraries > Keyboard and switch the src foulder.

