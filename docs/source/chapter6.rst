Chapter6 :Touch control magic lights on arm of robot
====================================================================

1.Preparation
-------------------

1.You should learn about the position of the magic lights in the arm of
hellobot；

2.You should learn about the principle of touch magic lights;

3.You should learn about the micro:bit pins connected to the magic
lights in the schematic.

|image0| |image1|

(a)touch magic lights on the left arm (b)touch magic lights on the right
arm |image2|

3-1-1 touch magic lights on arm of hellobot

The touch magic light is mounted on the two arms of the HelloBot robot,
one for each of the left and right arms. The touch magic light is a
whole module consisting of a touch module and a colorful water light.

|image3| |image4|

(a)magic lights (b)touch position

3-1-2 touch magic lights module

|image5|

3-1-3 about wiring

|image6|

3-1-4 schematic

|image7|

3-1-5 Pins of Micro:bit

From the schematic diagram in P3-1-5, you can see that the touch magic
lights is connected to the P6, P9 of the Micro:bit. And touch key is
connected to the P7, P10 of the Micro:bit.

Note:In the bottom layer of the HelloBot package has been set parameter
for the user, you can directly drag the touch magic lights building
blocks.

2. **Learning goals**

In this course, we learns how to control touch magic lights by touch
key.

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

|image8|

2) After entering the programming interface, you need to click Add
package and copy the HelloBot package URL:
https://github.com/lzty634158/HelloBot to the input field, click to
confirm the add package. Then you can use the blocks of the HelloBot
package.

Note: The package only needs to be added once. If you have added
packages in the previous lessons, this course does not need to be added
repeatedly.

|image9|

3-1-6 total program

The locations of blocks in the total program are shown in the following
figure.

|image10|

3-1-7

|image11|

3-1-8

|image12|

3-1-9

|image13|

3-1-11

|image14|

3-1-12

**4.Download programming**

You need to make sure that the micro:bit development board is connected
to the computer. Then you should click on the download in the lower left
corner as shown in P 3-1-13 to download the program to micro:bit.

|image15|

3-1-13

**5.Phenomenon**

After the code is uploaded. You need to put your hand on the touch
switch and

you will see that the magic light on the arm will switch color all the
time. When

the hand remove, the magic light will always show the color displayed
when

the hand leaves, until you touch it again.

|image16| |image17|

|image18| |image19|

3-1-14

.. |image0| image:: ./chapter6/media/image1.png
   :width: 2.43611in
   :height: 1.98611in
.. |image1| image:: ./chapter6/media/image2.png
   :width: 2.69375in
   :height: 1.98264in
.. |image2| image:: ./chapter6/media/image3.png
   :width: 5.23958in
   :height: 5.11181in
.. |image3| image:: ./chapter6/media/image4.png
   :width: 2.20903in
   :height: 1.76736in
.. |image4| image:: ./chapter6/media/image5.png
   :width: 1.88681in
   :height: 1.78958in
.. |image5| image:: ./chapter6/media/image6.png
   :width: 5.19097in
   :height: 3.60903in
.. |image6| image:: ./chapter6/media/image7.png
   :width: 4.38472in
   :height: 1.60417in
.. |image7| image:: ./chapter6/media/image8.png
   :width: 5.76250in
   :height: 5.27778in
.. |image8| image:: ./chapter6/media/image9.png
   :width: 0.93472in
   :height: 0.79514in
.. |image9| image:: ./chapter6/media/image10.png
   :width: 5.75833in
   :height: 1.90764in
.. |image10| image:: ./chapter6/media/image11.png
   :width: 4.85694in
   :height: 4.14028in
.. |image11| image:: ./chapter6/media/image12.png
   :width: 4.80000in
   :height: 3.75764in
.. |image12| image:: ./chapter6/media/image13.png
   :width: 5.76806in
   :height: 3.70278in
.. |image13| image:: ./chapter6/media/image14.png
   :width: 5.03611in
   :height: 3.56042in
.. |image14| image:: ./chapter6/media/image15.png
   :width: 5.12708in
   :height: 4.50625in
.. |image15| image:: ./chapter6/media/image16.png
   :width: 5.76806in
   :height: 2.09097in
.. |image16| image:: ./chapter6/media/image17.png
   :width: 2.35417in
   :height: 1.91389in
.. |image17| image:: ./chapter6/media/image18.png
   :width: 2.40556in
   :height: 1.88542in
.. |image18| image:: ./chapter6/media/image19.png
   :width: 2.51111in
   :height: 1.96181in
.. |image19| image:: ./chapter6/media/image20.png
   :width: 2.39931in
   :height: 1.95278in
