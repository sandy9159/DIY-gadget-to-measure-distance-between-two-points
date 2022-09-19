# DIY-gadget-to-measure-distance-between-two-points


![thum2](https://user-images.githubusercontent.com/19898602/190953425-f7668832-e6cc-450e-9a6b-426d32b39a24.jpg)


Hello friends in this video I have made a gadget to measure the distance between two point on flat surface remotely.
I have used ultrasonic sensor to calculate distance between the surface and gadget,

and measuring angle by MPU6050.
Then after getting data I have used basic trigonometry function to calculate the distance between those points. 
Yes this method is not much accurate but this just an Idea to implement. 


# Component required
1. Arduino Nano
2. Custom PCB
3. Ultrasonic sensor
4. 3D parts
5. Laser diods
6. lipo battery
7. HMI display
8. some hardwares

# Circuit diagram

For this project as usually I have used my multipurpose PCB
Those who ever worked with arduino they know the pain of connecting different components with arduino for there projects. so here is the answer for you all.
not 1 or 2 you can connect 11 components at same time & on board.

5V & 9V regulator, cross polarity protection, power indication LED, motor power selection provision (5V or 9V or 12V) manual provision for stepper motor microstepping setting. wide range of input supply (9V to 24V).

This is my multipurpose PCB works with Arduino Nano, I have designed it in a way that you can run 2 Stepper motors, 2 DC motors, 2 Servo motors at same time and this is not it you can even connect BT module, rotary encoder, I2C device, potentiometer at same time.

This PCB is very much helpful in building any project and no need to worry about messy wire connections.

![image](https://user-images.githubusercontent.com/19898602/190953901-cf4d5e36-5374-4682-b492-8a98495b59ba.png)

![image](https://user-images.githubusercontent.com/19898602/190953918-7b22a10d-de56-4778-9b25-cf9db314dae6.png)

I have design circuit and PCB in easyEDA and ordered PCB from [JLCPCB](https://jlcpcb.com/IAT )


[JLCPCB](https://jlcpcb.com/IAT ) are the world leader in PCB manufacturing there PCB production rates are very much affordable and they have world class PCB production unit results fast PCB production.

I have provided the link of circuit design so that you can modify it as per your need if you need to change anything.

[Multipurpose custom PCB](https://oshwlab.com/sharmaz747/multipurpose-pcb_copy_copy_copy)








This is the custom made PCB used in this project. by the way this is multipurpose PCB it can be used for wide range of arduino project.

If you are interested to order this PCB so you can find the Gerber file of the PCB here

JLCPB also started the 3D printing service if you have any requirement of 3D part you can surly visit JLCPCB

[Multipurpose custom PCB](https://oshwlab.com/sharmaz747/multipurpose-pcb_copy_copy_copy)


![image](https://user-images.githubusercontent.com/19898602/188255753-78070b6b-d726-4cac-8e2e-b27034581e03.png)

# Basic working principle

![image](https://user-images.githubusercontent.com/19898602/190954123-3949de83-8250-4cab-886f-5bbe26f48e87.png)


The fields that trigonometry is being used today for include electronics, engineering, and calculus.

A study of trigonometry will primarily involve concepts of angles, the right triangle, and the unit circle.

The problems you can solve with trigonometry are many. A short list includes the following:

Angle of elevation
Angle of depression
Height of a very tall building
Diameter of the moon
The area that is swept clean by a windshield wiper

![image](https://user-images.githubusercontent.com/19898602/190955634-c803f566-6628-45e6-a4bf-90afa50ed7a8.png)



![image](https://user-images.githubusercontent.com/19898602/190955748-b43d97f6-590e-4d8f-a6d5-6ba3bc953e01.png)

First I have made a wooden base with 12mm wooden sheet. 

I always use birch ply for my project because it looks good and easy to work with.

I cut the wooden sheet using Jigsaw machine and then I rounded the edge with 
The help of sander machine.


![image](https://user-images.githubusercontent.com/19898602/190956062-b5129761-8d3d-4ebd-83c3-aca1336792da.png)![image](https://user-images.githubusercontent.com/19898602/190956097-9ef6deba-d2a6-49c9-be6c-2ef4eb685083.png)

Ultrasonic Sensor HC-SR04 is a sensor that can measure distance. 

Here I use HC-SR04 Ultrasonic sensor yes this type of sensor are not very much accurate, but it will be ok for our proof of concept video.

It emits an ultrasound at 40 000 Hz (40kHz) which travels through the air and if there is an object or obstacle on its path It will bounce back to the module. Considering the travel time and the speed of the sound you can calculate the distance.

The configuration pin of HC-SR04 is VCC (1), TRIG (2), ECHO (3), and GND (4). The supply voltage of VCC is +5V and you can attach TRIG and ECHO pin to any Digital I/O in your Arduino Board.

![image](https://user-images.githubusercontent.com/19898602/190956336-67c239f5-e679-4fd9-a8e4-22326ad3dc12.png)


![image](https://user-images.githubusercontent.com/19898602/190956379-b8c11dee-78c3-4221-9896-36d184c50662.png)
![image](https://user-images.githubusercontent.com/19898602/190956406-50cb1ae3-6945-42a6-862d-60b68f248ad1.png)


Here I have use the laser diode for pointing the projection of point in the flat surface.

You have to be caution while working with laser lights do not through it directly to your eys.
Also wear protective eye glasses while working with lasers.

This mini laser diode are working on 5V DC also this tinny diode have focus adjustment knob in front
Part of the laser body. 


![image](https://user-images.githubusercontent.com/19898602/190956715-3b9bdc04-439e-4992-9239-f225bb1bd31a.png)

In this project I have MPU6050 gyroscope sensor .

The MPU-6050 is the world’s first and only 6-axis motion tracking devices designed for the low power, low cost, and high performance requirements of smartphones, tablets and wearable sensors.

![image](https://user-images.githubusercontent.com/19898602/190956865-9e2f256c-b490-4e71-a8aa-19aaecceadcc.png)





