# SMD-Reflow-Hot-Plate
My Build of  John Bradnam   SMD Reflow Hot Plate

Using the Ant PCB Maker I built a couple years back, https://www.youtube.com/@TheAntPCBMaker

I put it to the test of making this small SMD components with a ATTINY3224.
You can fine the complete build here: https://www.hackster.io/john-bradnam/smd-reflow-hot-plate-new-version-edc02e
What I did diffrent on the third try, I enlarged all the traces and pads to big as i could in KiCad. reason is the V bit will eat away your traces as you can see on the first try (first picture on the right on board on Ant Milling Machine).
I used FlatCAM  and did one pass @ .1 V bit and multipassing down twice to .07mm 

This is second failer, I forgot to mirror the board!
![20231225_092138](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/eae0adcb-ec9e-4316-9593-88199dbef1d3)

This is the third try ( strike three your out)!

![20231225_164304](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/7a7e84c4-0369-46b3-a085-a87fee0a71cc)

![20231225_164321](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/58bac2bc-ebcf-4a93-9c25-e31f11ea9ef1)

Now to get the parts soldered on.....

Parts layout  

 ![Bottom_Comp](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/89b80095-a8eb-4119-8375-d7019a1ea280)

Fourth time 2 passes .1 bit

![WIN_20231228_07_57_30_Pro](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/87ab76cd-9e03-4c5d-ba81-d1139ff66ae7)

![image](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/cc24d6a4-5ef1-457c-b602-1e8a0227982a)

![image](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/a4cf8bb5-257d-4ee3-8117-4ab34cff983c)

All seems working except for turning on the heat (more trouble shooting) the temp readings or from me using a bic lighter.

![image](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/ace4ee9c-d2cd-4d94-b570-9261bd0ef0b0)

Some test points 
![image](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/03c1d2de-2e4e-47c5-9697-94ef896a670c)

![Bottom_Comp_Test_Points-2](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/a1806273-5f18-4fc5-a8f3-09abf1fcf88c)
Still not winning getting the relay to come on when suppose too, seems a loose connection somewhere!

I ordered from JPC the boards before doing the CNC engraving, today they or comming in so I will solder up a board 

![Screenshot 2023-12-26 093402](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/150dce43-9ac8-489b-8f62-8742cab13193)

![Screenshot 2023-12-26 093212](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/8ce24ee6-8165-4469-9444-18038aef7197)

JLC Made boards
Shipping:
USD $1.50
Subtotal:
USD $2.00
Sales tax:
USD $0.16
Grand Total:
USD $3.66

![image](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/b7acc5c9-3c51-4bc9-a4a5-0cfaeb5fe7c6)

![image](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/1ef02638-b463-46de-80ba-7631120370d1)


Trouble shooting the new JLC made board with the CNC engraved board, I found the bad trace and was able to get the Engraved board working!
the trouble with the new board was the 20hz , set it to 16Hz and screen worked fine.

![image](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/b142189b-2b1a-4586-9d2e-8903df56361b)

I had some silicone pad from a broken shirt press, I used it for heat insulation.
![image](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/037704ff-5ddc-4159-b4ab-13e3e21f0099)

When I had trouble with New JLC made board with the display, I though maybe the Chip was damaged. I removed it with hot air gun and replaced it. It was soon that I tryed changing the Hz from 20 to 16 that fixed the problem! I remember John Bradnam saying that in his build instrutions. I used the chip as first test with hot plate, using 183 C solder paste, put the chip on this developing board and ran the led blink test on all 10 pins, chip was fine. How i did that was setup a blink  code and did a single led with a 220R resistor and used a jumper wire to touch each pin to verify the pin is blinking the Led.

![image](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/967cd22d-812c-45fe-8bdb-870e61b7364f)


Blink_Test_ATtiny3224_All_Pins_1-10.zip

![image](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/6ad4e435-66de-4e02-8334-8e5c7b658378)

I used Silicone Thermal Heatsink Plaster to hold thermocouple to middle bottom of heat plate.
It does not get hard and hold really well.
I had some that I always use for 3d printers to hold heat sink on stepper drivers.

![image](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/7d7dc01a-fa0a-47df-8e6e-f2d0af1b31f7)

Made a New Toy! to remove single parts

![WIN_20240105_16_04_40_Pro](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/38533571-e75f-47ec-bf62-ac5714987f08)

This sound board went bad with a humming, it is used in a talking clock.
I removed a good Cap by the mic that I was not using and replaced the burt cap. this fixed the humming and talking Clock is working again.

![WIN_20240105_17_17_52_Pro](https://github.com/carl1961/SMD-Reflow-Hot-Plate/assets/3056821/0473e19c-5ea7-4ddb-9516-9da7964dd211)

Video's of me doing this and the files to make the Mini hot plate or in github folder. This uses a Hotend from a 3d printer. I removed the double Heat bar to just one, as it was taking to long to heat the board.


















I will update as I get something to show.


