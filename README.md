This is a VHDL based retro video game. We are in Bilkent University's EEE Department, trying to pass EEE 102 Introduction to Digital Design Course (the course whose term project is this project) by collecting the red dots. Go to right or leftmost edges of the screen and push up/down buttons to change the floor displayed in the middle of the screen. Find the red dots before the timeout!

Check out [1] for a cooler Verilog version! I used the bmp to coe file generator code to embed my pixel art to Basys3. The binary file is available as topmodule.bit, you can put the binary file to a USB and change the programming jumper (right next to the USB port of BASYS3) from JTAG to USB, connect the USB to the BASYS3, connect a VGA cable to a screen (computer or TV should work) and you are ready to play! Use BASYS3's pushbuttons to start and play the game.


References 

[1] Embedded Thoughts. “Yoshi's Nightmare: FPGA Based Video Game.” Embedded Thoughts,
9 Dec. 2016, embeddedthoughts.com/2016/12/09/yoshis-nightmare-fpga-based-videogame/.
