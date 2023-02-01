# Arcade-Machine 
We are demonstrating how to build full bartop arcade by using raspberry pi 4 
Our main purpose in this project is to entertain and to bring back the legacy that is left behind during the golden age of gaming for the 90s kids.


# Final Output: 
![this is an image](https://github.com/NaNo211/Arcade-Machine/blob/main/Arcade-machine.jpeg)


# Steps:
1. we searched for the CNC Arcade body and thanks for grabcade we foud a suitable 3D design [here](https://grabcad.com/library/bartop-arcade-cabinet-wip-1) and you will find the f3d file in the repository, however we did some modifications to fit for our components. 

2. Components used:
    - Raspberry Pi 4 2GB RAM.
    - LCD 19 INCH.
    - LCD Controller Board.
    - LCD Power Board.
    - Joysticks.
    - Push Buttons.
    - Micro Switches.
    - Speakers.
    - Power adapter for raspberry pi.
    - Arcade encoder for joysticks and push buttons.
    
3. We desinged our Schematic for the connections, you will find the .fzz file [here](https://github.com/NaNo211/Arcade-Machine/blob/main/design.fzz).

4. We installed an the "Recallbox" emulator in the raspberry. The link [here](https://www.recalbox.com).

5. We started to mount the connections:
    - For the controller setup : we couldn't get an arcade encoder, however we found a suitable alternative thanks for Alan Chatham as he used an Arduino Uno or Arduino mega as a PS3-compatible USB game controller, you will find the steps [here](https://github.com/AlanChatham/UnoJoy ). So we used 2 Arduino uno for this project and it's very well.
    - For the display: we used 19 philips monitor and we attached LCD controller board for the analog signals you will find it on amazon [here](https://www.amazon.com/VSDISPLAY-Controller-LP140WH1-BT140XW02-Backlight/dp/B01N5J57YP/ref=sr_1_6?keywords=lcd+controller+board&qid=1644002950&sr=8-6) and the powerboard that we used the LCD [here](https://www.aliexpress.com/item/32814652731.html).
    - For the sound system: we used 2 x 10Watt speakers and amplifier connteced to raspberry pi 4 however maker sure the amplifier can handel 2 channel 10Watt.
    - Final touches: we tweak our project by adding some posters and put RGB lights controlled by the sound system.


# Updates :
We are still updating the project by putting a coin acceptor and make the arcade portable so make sure to wait for the update.
For any information contact nadaSamir@student.aast.edu or nourmorse21@gmail.com.
