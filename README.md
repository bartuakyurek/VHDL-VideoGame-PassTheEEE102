This is a VHDL based retro video game for the EEE 102 term project. Short YouTube demo can be found [here](https://www.youtube.com/watch?v=GrdW-8Rqzqo&t=62s). We are in Bilkent University's EEE Department, trying to pass EEE 102 Introduction to Digital Design Course by collecting the red dots. Go to right or leftmost edges of the screen and push up/down buttons to change the floor displayed in the middle of the screen. Find the red dots before the timeout!

Check out [1] for a cooler Verilog version! I used their bmp to coe file generator code to embed my pixel art to Basys3. The binary file is available as topmodule.bit, you can put the binary file to a USB and change the programming jumper (right next to the USB port of BASYS3) from JTAG to USB, connect the USB to the BASYS3, connect a VGA cable to a screen (computer or TV should work) and you are ready to play! Use BASYS3's pushbuttons to start and play the game.

<img width="543" alt="Ekran Resmi 2019-03-14 22 47 58" src="https://user-images.githubusercontent.com/77360680/118501123-13e53100-b731-11eb-96c3-1b77f180b318.png">

<img width="900" alt="Screen Shot 2021-05-17 at 17 04 31" src="https://user-images.githubusercontent.com/77360680/118502583-81459180-b732-11eb-8922-efb849c71dbd.png">

<img width="503" alt="Screen Shot 2021-05-17 at 17 04 16" src="https://user-images.githubusercontent.com/77360680/118502415-5a875b00-b732-11eb-8c12-a165f1973b4a.png">

#### References 

[1] Embedded Thoughts. “Yoshi's Nightmare: FPGA Based Video Game.” Embedded Thoughts,
9 Dec. 2016, embeddedthoughts.com/2016/12/09/yoshis-nightmare-fpga-based-videogame/.
