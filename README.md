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





