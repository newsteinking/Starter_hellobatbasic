Chapter12 :헬로봇 추척하기
====================================================================

1.Preparation
----------------------

1.You should learn about the position of the RGB tracking obstacle
avoidance 3 in 1 module in the body of hellobot；

2.You should learn about the principle of the tracking.

|image0|

 7-2-1 RGB tracking obstacle avoidance 3 in 1 module

|image1|

7-2-2 RJ45 interface of RGB tracking obstacle avoidance 3 in 1 module

|image2| |image3|

(a) Back of module (c) Front of module

7-2-3 RGB tracking obstacle avoidance 3 in 1 module

|image4|

7-2-4 RJ45 interface and cable

The RGB tracking obstacle avoidance 3 in 1 module is installed under the
robot arm of the HelloBot, and we need to use the network cable to
connect the RGB tracking obstacle avoidance 3 in 1 module.

|image5|

7-2-5 schematic

|image6|

7-2-6 Pins of Micro:bit

From the schematic diagram. You can see that left probe is connected to
P1 of Micro:bit, right probe is connected to P1 of Micro:bit, colorful
lights is connected to P5 of Micro:bit.

Principle of tracking: The basic principle of the infrared tracking
sensor is to take advantage of the reflective nature of the object. When
the infrared light is emitted onto the black line, it will be absorbed
by the black line, but when the infrared light is emitted onto the other
colors line, it will be reflected onto the infrared receiver pin. When
the car's tracking module detect the black line, the indicator light is
light up, and when the white object was detected, the indicator light is
light out.

According to this, we write the corresponding code to make the car
complete tracking function.

**Note:**\ The tracking sensor is not working properly due to the
interference of outdoor light. This course needs to be carried out
indoors and the curtains are covered to block the outdoor light.

\ **2.Learning goals**

In this experiment, we need the effect that the robot car walk along the
black line.

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

|image7|

2) After entering the programming interface, you need to click Add
package and copy the HelloBot package URL:
https://github.com/lzty634158/HelloBot to the input field, click to
confirm the add package. Then you can use the blocks of the HelloBot
package.

Note: The package only needs to be added once. If you have added
packages in the previous lessons, this course does not need to be added
repeatedly.

|image8|

7-2-7 total program

The locations of blocks in the total program are shown in the following
figure.

|image9|

7-2-8 |image10|

7-2-10

**4.Download programming**

You need to make sure that the micro:bit development board is connected
to the computer. Then you should click on the download in the lower left
corner as shown in P 7-2-11 to download the program to micro:bit.

|image11|

7-2-11

**5.Phenomenon**

After the code is uploaded. We will see that the HelloBot walk along the
black line.

|image12|

7-2-12

.. |image0| image:: ./chapter12/media/image1.png
   :width: 4.72431in
   :height: 3.95972in
.. |image1| image:: ./chapter12/media/image2.png
   :width: 3.28056in
   :height: 2.73958in
.. |image2| image:: ./chapter12/media/image3.png
   :width: 2.45486in
   :height: 2.20972in
.. |image3| image:: ./chapter12/media/image4.png
   :width: 2.22500in
   :height: 2.24583in
.. |image4| image:: ./chapter12/media/image5.png
   :width: 5.76389in
   :height: 5.79167in
.. |image5| image:: ./chapter12/media/image6.png
   :width: 3.34583in
   :height: 2.99097in
.. |image6| image:: ./chapter12/media/image7.png
   :width: 4.59722in
   :height: 4.22292in
.. |image7| image:: ./chapter12/media/image8.png
   :width: 0.93472in
   :height: 0.79514in
.. |image8| image:: ./chapter12/media/image9.png
   :width: 5.76806in
   :height: 1.76667in
.. |image9| image:: ./chapter12/media/image10.png
   :width: 3.97222in
   :height: 3.16319in
.. |image10| image:: ./chapter12/media/image11.png
   :width: 5.76806in
   :height: 2.05069in
.. |image11| image:: ./chapter12/media/image12.png
   :width: 5.76806in
   :height: 2.31319in
.. |image12| image:: ./chapter12/media/image13.png
   :width: 5.76250in
   :height: 3.86667in
