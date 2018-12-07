**10-1.Infrared remote control**

\ **1.Preparation**

1.You should learn about the position of the infrared receiver in the
body of hellobot；

2.You should learn about the principle of the infrared infrared
receiver.

|image0|

10-1-1 position of the infrared receiver in the body of hellobot

The infrared receiver is integrated on the left side of the expansion
board. When you use the infrared remote controller, the remote
controller needs to be aligned with the infrared receiver to receive the
signal and perform corresponding actions.

|image1|

10-1-2 schematic

|image2|

10-1-3 Pins of Micro:bit

From the schematic diagram. You can see that infrared receiver is
connected to P8 of Micro:bit. Therefore, in the program, it is necessary
to initialize the infrared receiving pin, and then you can write the
program to set the action corresponding to the key value of the infrared
remote control.

**Infrared remote control principle:**

**The infrared remote control emits modulated infrared light waves; the
infrared receiver receives the infrared signals and converts them into
corresponding electrical signals, which are then sent to the post
amplifier. In this experiment, we used an infrared remote controller to
control the movement of the car.**

**Note:**\ The infrared obstacle avoidance sensor is not working
properly due to the interference of outdoor light. This course needs to
be carried out indoors and the curtains are covered to block the outdoor
light.

|image3|

10-1-4 Infrared remote control code value

// 00FF00FF |image4| red\_colorful lights

// 00FF30CF |image5| blue\_colorful lights

// 00FF708F |image6| purple\_colorful lights

// 00FF40BF |image7| green\_colorful lights

// 00FFA05F |image8| stop

// 00FF807F |image9|\ advance

// 00FF20DF |image10|\ turn left

// 00FF609F |image11|\ turn right

// 00FF906F |image12|\ back

// 00FF10EF |image13|\ turn left in place

// 00FF50AF |image14|\ turn right in place

// 00FFB04F 0 sing

// 00FF08F7 1 green\_arm colorful lights

// 00FF8877 2 red\_arm colorful lights

// 00FF48B7 3 yellow\_arm colorful lights

// 00FF28D7 4 Control the servo rotation of J2 interface

// 00FFA857 5 white\_arm colorful lights

// 00FF6897 6 Control the servo rotation of J3 interface

// 00FF18E7 7 Control the servo rotation of J2 interface

// 00FF9867 8 blue\_arm colorful lights

// 00FF58A7 9 Control the servo rotation of J3 interface

**2.Learning goals**

In this course, we will study how to control car by infrared controller.

**3.Programming**

3.1 Programming online

1) You should use the USB cable to connect the micro:bit to the
computer, at this point, the computer will have a micro:bit U disk. You
need to open it, click micro:bit website, then entered the micro:bit
website or you can enter the URL directly in your browser:
http://microbit.org/

2) After entering the programming interface, you need to click Add
package and copy the HelloBot package URL:
https://github.com/lzty634158/HelloBot to the input field, click to
confirm the add package. Then you can use the blocks of the HelloBot
package.

3.2 Programming offline

1) You can double-click to use it. As shown in the following figure.

|image15|

2) After entering the programming interface, you need to click Add
package and copy the HelloBot package URL:
https://github.com/lzty634158/HelloBot to the input field, click to
confirm the add package. Then you can use the blocks of the HelloBot
package.

Note: The package only needs to be added once. If you have added
packages in the previous lessons, this course does not need to be added
repeatedly.

|image16|

10-1-5 total program

The locations of blocks in the total program are shown in the following
figure.

|image17|

10-1-6

|image18|

10-1-7

|image19|

10-1-8

|image20|

10-1-9

**4.Download programming**

You need to make sure that the micro:bit development board is connected
to the computer. Then you should click on the download in the lower left
corner as shown in P 10-1-10 to download the program to micro:bit.

|image21|

10-1-10

**5.Phenomenon**

After the code is uploaded. You can control HelloBot by infrared remote
controller. When you press |image22| and “2” key, colorful lights and
arm color lights are become red. When you press |image23| and “5” key,
colorful lights are become blue and arm color lights are become green.
As shown in the following figure. (Just for example)

|image24| |image25|

(a) (b)

10-1-11

.. |image0| image:: media/image1.png
   :width: 5.76181in
   :height: 4.92986in
.. |image1| image:: media/image2.png
   :width: 3.15556in
   :height: 2.60417in
.. |image2| image:: media/image3.png
   :width: 5.76667in
   :height: 5.30972in
.. |image3| image:: media/image4.png
   :width: 4.47847in
   :height: 4.58264in
.. |image4| image:: media/image5.png
   :width: 0.36806in
   :height: 0.31111in
.. |image5| image:: media/image6.png
   :width: 0.33958in
   :height: 0.37708in
.. |image6| image:: media/image7.png
   :width: 0.33958in
   :height: 0.35833in
.. |image7| image:: media/image8.png
   :width: 0.35833in
   :height: 0.39653in
.. |image8| image:: media/image9.png
   :width: 0.33958in
   :height: 0.32986in
.. |image9| image:: media/image10.png
   :width: 0.37708in
   :height: 0.35833in
.. |image10| image:: media/image11.png
   :width: 0.35833in
   :height: 0.32986in
.. |image11| image:: media/image12.png
   :width: 0.33958in
   :height: 0.33958in
.. |image12| image:: media/image13.png
   :width: 0.39653in
   :height: 0.37708in
.. |image13| image:: media/image14.png
   :width: 0.32986in
   :height: 0.33958in
.. |image14| image:: media/image15.png
   :width: 0.32986in
   :height: 0.35833in
.. |image15| image:: media/image16.png
   :width: 0.93472in
   :height: 0.79514in
.. |image16| image:: media/image17.png
   :width: 5.76806in
   :height: 4.43194in
.. |image17| image:: media/image18.png
   :width: 5.29097in
   :height: 6.20764in
.. |image18| image:: media/image19.png
   :width: 5.76806in
   :height: 4.04028in
.. |image19| image:: media/image20.png
   :width: 5.63472in
   :height: 5.18681in
.. |image20| image:: media/image21.png
   :width: 5.76806in
   :height: 3.93264in
.. |image21| image:: media/image22.png
   :width: 5.76806in
   :height: 2.91389in
.. |image22| image:: media/image5.png
   :width: 0.36806in
   :height: 0.31111in
.. |image23| image:: media/image6.png
   :width: 0.33958in
   :height: 0.37708in
.. |image24| image:: media/image23.png
   :width: 2.64514in
   :height: 2.31597in
.. |image25| image:: media/image24.png
   :width: 2.45486in
   :height: 2.32569in
