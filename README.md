# openFPGA-Coleco
Coleco core for openFPGA on Analogue Pocket
-

Regular, Super Game Module, EEPROM, and flash games are supported by this core.

You must place the Colecovision BIOS, named "coleco.bin" into the 

/assets/coleco/Spiritualized.Coleco/ folder!  It should be 8192 bytes in size.

These games utilize save memory and must have the correct extention to work:

Black Onyx should have the .CE0 file extention, Boxxle needs the .CE1 extension, and Penguin Adventure and Gradius need a .CF0 extension.

Because the Coleco has a number pad, typing the numbers in is
normally impossible.  You can still type them in, however, using
button chords:

L trigger + up = 0  
L trigger + right = 1  
L trigger + down = 2  
L trigger + left = 3  

R trigger + up = 4  
R trigger + right = 5  
R trigger + down = 6  
R trigger + left = 7  

L+R trigger + up = 8  
L+R trigger + right = 9  

Almost nothing uses the number pads except to select difficulty
level at the start of a game.

Several of the buttons have been mapped to make starting games
easier:

Start - #  
Select - *  
Y = 1  
X = 3  
B = left button  
A = right button  
