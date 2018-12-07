**Chapter10 :HelloBot sing dance arm swing**

\ **1.Preparation**

1.You should learn about the position of the motors in the body of
hellobot；

2.You should learn about the principle of the motors.

3.You should learn how to drive the motors with the PCA9685PW.

|image0| |image1|

(a)Left motor on the hellobot (b)Right motor on the hellobot

|image2|

6-2-1 two motors

The HelloBot robot uses two yellow TT DC gear motors, and the rotation
of the motor drives the wheel forward. The motor on the left is
connected to the left side of the expansion board, and the motor on the
right is connected to the right side of the expansion board.

|image3|

6-2-2 servos on arm of hellobot

Tow servos is the robot's joint, which is mounted on the two arms of the
HelloBot. You can control servos rotate degree to control arms.

|image4|\ 6-2-3 buzzer on arm of hellobot

You need to look forward from the back of the robot, the left servo is
connected to the J3 interface, and the right servo is connected to the
J2 interface. The brown line of the servo corresponds to GND, the red
line corresponds to VCC, and the yellow line corresponds to IO.

|image5|

6-2-4 schematic of servo

|image6|

6-2-5 schematic of motor drive

|image7|

6-2-6 schematic of buzzer

|image8|

6-2-7 schematic of PCA9685PW

|image9|

6-2-8 Pins of Micro:bit

From the schematic diagram. You can see that tow motors is connected to
LINA(12)、LINB(13)、RINA(14)、RINB(15) of PCA9685PW.

PCA9685PW is a 16-bit LED controller with IIC bus interface. Each LED
can output 12-bit resolution (4096 levels) fixed-frequency independent
PWM.

2. **Learning goals**

In this course, we will learn how to make HelloBot robot advance, back,
turn left, turn right, arm swing, sing, dance.

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

|image10|

2) After entering the programming interface, you need to click Add
package and copy the HelloBot package URL:
https://github.com/lzty634158/HelloBot to the input field, click to
confirm the add package. Then you can use the blocks of the HelloBot
package.

Note: The package only needs to be added once. If you have added
packages in the previous lessons, this course does not need to be added
repeatedly.

|image11|

(a)

|image12|

(b)

|image13|

(c)

|image14|

(d)

|image15|

(e)

|image16|

(f)

6-2-9 total program

The locations of blocks in the total program are shown in the following
figure.

|image17|

6-2-10

|image18|

6-2-11

|image19|

6-2-12

**4.Download programming**

You need to make sure that the micro:bit development board is connected
to the computer. Then you should click on the download in the lower left
corner as shown in P 6-2-13 to download the program to micro:bit.

|image20|

6-2-13

**5.Phenomenon**

After the code is uploaded. HelloBot start to play music, and advance,
back, turn left, turn right, arm swing.

|image21|

6-2-14

.. |image0| image:: ./chapter10/media/image1.png
   :width: 2.56042in
   :height: 1.67847in
.. |image1| image:: ./chapter10/media/image2.png
   :width: 2.55903in
   :height: 1.67708in
.. |image2| image:: ./chapter10/media/image3.png
   :width: 3.86458in
   :height: 4.83194in
.. |image3| image:: ./chapter10/media/image4.png
   :width: 5.76458in
   :height: 4.34722in
.. |image4| image:: ./chapter10/media/image5.png
   :width: 5.76181in
   :height: 5.87847in
.. |image5| image:: ./chapter10/media/image6.png
   :width: 1.31250in
   :height: 4.39514in
.. |image6| image:: ./chapter10/media/image7.png
   :width: 5.76181in
   :height: 3.14792in
.. |image7| image:: ./chapter10/media/image8.png
   :width: 3.66597in
   :height: 3.71806in
.. |image8| image:: ./chapter10/media/image9.png
   :width: 5.76250in
   :height: 3.93681in
.. |image9| image:: ./chapter10/media/image10.png
   :width: 5.48472in
   :height: 4.89722in
.. |image10| image:: ./chapter10/media/image11.png
   :width: 0.93472in
   :height: 0.79514in
.. |image11| image:: ./chapter10/media/image12.png
   :width: 5.76806in
   :height: 5.90764in
.. |image12| image:: ./chapter10/media/image13.png
   :width: 5.76806in
   :height: 4.43194in
.. |image13| image:: ./chapter10/media/image14.png
   :width: 5.76806in
   :height: 4.64028in
.. |image14| image:: ./chapter10/media/image15.png
   :width: 5.76806in
   :height: 6.79028in
.. |image15| image:: ./chapter10/media/image16.png
   :width: 5.76806in
   :height: 6.02708in
.. |image16| image:: ./chapter10/media/image17.png
   :width: 5.61389in
   :height: 3.24931in
.. |image17| image:: ./chapter10/media/image18.png
   :width: 5.29097in
   :height: 6.30139in
.. |image18| image:: ./chapter10/media/image19.png
   :width: 5.76806in
   :height: 4.35000in
.. |image19| image:: ./chapter10/media/image20.png
   :width: 5.76250in
   :height: 4.17639in
.. |image20| image:: ./chapter10/media/image21.png
   :width: 5.76806in
   :height: 4.56319in
.. |image21| image:: ./chapter10/media/image22.png
   :width: 3.34097in
   :height: 3.13542in
