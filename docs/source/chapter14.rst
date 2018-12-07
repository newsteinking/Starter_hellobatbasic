Chapter14 :Avoid_ultrasonic
====================================================================

1.Preparation
-----------------------

1.You should learn about the position of the Ultrasonic module in the
body of hellobot；

2.You should learn about the principle of the Ultrasonic module.

|image0| |image1|

8-2-1 position of Ultrasonic module 8-2-2 position of wiring

Both the ultrasonic interface and the expansion board interface are
designed with anti-reverse connection. The ultrasonic module is
connected to the left side of the expansion board by the 4Pin cable.

|image2|

8-2-3 schematic of ultrasonic module

|image3|

8-2-4 schematic of motor drive

|image4|

8-2-5 schematic of PCA9685PW

|image5|

8-2-6 Pins of Micro:bit

From the schematic diagram. You can see that Pin \_Trig of ultrasonic
module(SCL) is connected to P14 of Micro:bit, Pin\_Echo of ultrasonic
module(SDA) connected to P15 of Micro:bit.

PCA9685PW connects micro:bit P19 and P20 pins for I2C communication.

Principle of ultrasonic module:

1)The ultrasonic module is a sensor that uses ultrasonic characteristics
to detect the distance. It has two ultrasonic probes for transmitting
and receiving ultrasonic waves. The range of measurement is 3-450 cm.

2)You need to input a high level signal of at least 10us to the Trig pin
to trigger the ranging function of the ultrasonic module.

3)After the ranging function is triggered, the module will automatically
send out 8 ultrasonic pulses with 40 kHz and automatically detect
whether there is a signal return. This step is done internally by the
module.

4)When the module detects an echo signal, the ECHO pin will output a
high level. The high level duration is the time from when the ultrasonic
wave is sent to when it returns. You can calculate the distance by using
the time function to calculate the high level duration.

**Formula: Distance = High level duration \* Speed of sound(340M/S)/2.
**

**2.Learning goals**

When the HelloBot robot in a paper box circle. When the robot detects an
obstacle in front, it will turn left to avoid the obstacle.

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

|image6|

2) After entering the programming interface, you need to click Add
package and copy the HelloBot package URL:
https://github.com/lzty634158/HelloBot to the input field, click to
confirm the add package. Then you can use the blocks of the HelloBot
package.

Note: The package only needs to be added once. If you have added
packages in the previous lessons, this course does not need to be added
repeatedly.

|image7|

8-2-7 total program

The locations of blocks in the total program are shown in the following
figure.

|image8|

8-2-8

|image9|

8-2-9

|image10|

8-2-10

**4.Download programming**

You need to make sure that the micro:bit development board is connected
to the computer. Then you should click on the download in the lower left
corner as shown in 8-2-11 to download the program to micro:bit.

|image11|

8-2-11

**5.Phenomenon**

After the code is uploaded. When the HelloBot robot in a paper box
circle. When the robot detects an obstacle in front, it will turn left
to avoid the obstacle.

|image12|

8-2-13

.. |image0| image:: ./chapter14/media/image1.png
   :width: 2.47014in
   :height: 3.05833in
.. |image1| image:: ./chapter14/media/image2.png
   :width: 2.67292in
   :height: 3.04722in
.. |image2| image:: ./chapter14/media/image3.png
   :width: 3.71806in
   :height: 2.63542in
.. |image3| image:: ./chapter14/media/image4.png
   :width: 5.76181in
   :height: 3.14792in
.. |image4| image:: ./chapter14/media/image5.png
   :width: 5.76319in
   :height: 3.97222in
.. |image5| image:: ./chapter14/media/image6.png
   :width: 5.14028in
   :height: 4.68819in
.. |image6| image:: ./chapter14/media/image7.png
   :width: 0.93472in
   :height: 0.79514in
.. |image7| image:: ./chapter14/media/image8.png
   :width: 5.02021in
   :height: 2.17681in
.. |image8| image:: ./chapter14/media/image9.png
   :width: 4.08264in
   :height: 3.15556in
.. |image9| image:: ./chapter14/media/image10.png
   :width: 5.76806in
   :height: 2.25347in
.. |image10| image:: ./chapter14/media/image11.png
   :width: 4.44444in
   :height: 4.39236in
.. |image11| image:: ./chapter14/media/image12.png
   :width: 5.76806in
   :height: 2.70278in
.. |image12| image:: ./chapter14/media/image13.png
   :width: 5.76667in
   :height: 6.01319in
