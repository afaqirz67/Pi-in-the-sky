# Pi-in-the-sky


Table of Contents:
* [CONSTRAINS](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#constraints)
* [SOLUTION](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#solution)
* [COMPONENTS](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#components)
* [RESOURCES](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#resources)
* [PARTS EXPLAINED](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#parts-explained)
* [SAFETY PROTOCOLS](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#safety-protocols)
* [DEADLINES](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#deadlines)
* [CAD DESIGNS](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#cad-designs)
* [SUGGESTIONS](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#suggestions)



## Planning 
### Goal
We have to make some sort of electronic creation using a raspberry pi that flies into the air and records data when it is at its apex height.data.

We want to make a drone using a pi that flies into the air and has a compartment that can drop things. aLthough it sounds simple, we want the drone to have a specific 
function. It should drop seeds to help the environment or have extra long battery life in order to be able to deliver things.

### Constraints
* The idea of a drone with a controller relies on radio communication with the drone. We have no idea how that works so we have to learn about it and overcome any obstacles we may encounter when using the radio communication and the raspberry pie.
Drones are very hard to make and if we want to have a special drone, it will take lots of tests and therefore time. This project will take tons of research to fully complete. We will have to specifically research each aspect of the project and plan out the physics of it. 
Live streaming of 360 cameras with VR is another obstacle to be overcomed and needs a significant amount of research and analysis


________________________________________________________________________________________________

#### Very Rough Sketches:

[Example of how our model will look like](https://www.youtube.com/watch?v=LVoPGlNvHhw)

#### Very Rough Designs 
[Learn Robotics](https://www.learnrobotics.org/blog/3d-printed-drones-thingiverse/)

### Solution


To be added...
________________________________________________________________________________________________

### SPICY PART:

Gesture control over the drone. We are thinking about using accelerometers or medical chips to match the movement of our hand to the movement of the drone.
We may want to control the drone using just the movment of our hand. This is a very rough idea and we will work on it once we know we can make a working drone. 

Another idea is to use gravity sensor for the hand gesture flight control, but we do not have prior knowledge of how this system of flight in drones work. We will need to dig 
deep into that. The concerning part for the moment is figuring out the exact boards and chips we will use and also the communication between the drone and your hand.

### Components 

[Brushless Motor](https://rctimer.com/dys-samguk-series-wei-2207-2300kv-2600kv-brushless-motor-for-rc-drone-fpv-racing-p1094.html)      

RPM = kv*volts


[Speed Controller](https://www.rcelectricparts.com/30a-rc-brushless-motor-electric-speed-controller-esc-3a-ubec-with-xt60--35mm-bullet-plugs.html)

[Transmitter & Reciever](https://www.amazon.com/Flysky-FS-i6X-Transmitter-FS-iA6B-Receiver/dp/B0744DPPL8/ref=sr_1_10?crid=288X7LG7SWQRI&keywords=rc+controller&qid=1652710949&sprefix=rc+controller%2Caps%2C60&sr=8-10)

[Fight controller](https://www.amazon.com/Accessories-Control-Controller-Quadcopter-Version/dp/B08B5TB9NR/ref=sr_1_3?keywords=spracing+f3+flight+controller&qid=1652711214&sprefix=spracing+f%2Caps%2C52&sr=8-3)   

[Battery](https://www.amazon.com/Venom-5000mAh-Battery-Universal-Traxxas/dp/B004YNQX7S?ref_=ast_sto_dp)

[Camera](https://www.google.com/shopping/product/1?q=wifi+module+for+drones&prds=epd:3335392841495737051,eto:3335392841495737051_0,pid:3335392841495737051&sa=X&ved=0ahUKEwiOivyMgYf2AhXAl3IEHZFsCxgQ9pwGCAk)

[Props](https://www.amazon.com/12pcs-iFlight-Nazgul-Tri-Blades-Propellers/dp/B095YLKJ37/ref=sr_1_5?keywords=5+inch+drone+propeller&qid=1652712063&sprefix=5+inch+droene+prop%2Caps%2C56&sr=8-5)

[Battery Connector](https://www.amazon.com/Connector-Extension-RC-Helicopter-Quadcopter/dp/B0754JKHWW/ref=sr_1_3_sspa?keywords=xt60+parallel+connector&qid=1647396029&sprefix=xt60+para%2Caps%2C93&sr=8-3-spons&psc=1&smid=A2G15BXXX6915N&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyNUdOMlo1TUtGUzE1JmVuY3J5cHRlZElkPUEwMDQ1MjcxS1lEMlJLQUZGUUFLJmVuY3J5cHRlZEFkSWQ9QTEwMTcwOTkxMzZBMTE1TFRaVDFIJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)



________________________________________________________________________________________________
# [Back to the TOP](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#pi-in-the-sky)

## Resources

* [How DC brushless motors work?](https://www.youtube.com/watch?v=bCEiOnuODac)
* [MOTOR POWER SUPPLY SPECIFICATIONS](https://www.hobbywing.com/products/enpdf/2205-2300KV.pdf)
* [Arduino Brushless Motor Control Tutorial | ESC | BLDC](https://howtomechatronics.com/tutorials/arduino/arduino-brushless-motor-control-tutorial-esc-bldc/)
* [HOW TO USE/WIRE FLIGHT CONTROLLER](https://www.youtube.com/watch?v=yIEAu8ig6V0)
* [Drone motor calculator](https://www.omnicalculator.com/other/drone-motor)
* [Info on Weight Ratio](https://top-10-drones.com/choose-motor-propeller-quadcopter/)
* [Motor specifications](https://www.getfpv.com/dys-samguk-series-wei-2207-2300kv-motor.html)



![pasted image 0](https://user-images.githubusercontent.com/56890879/152362260-7c9233a2-e19b-481a-9829-89f53286319e.png)
![pasted image 0 (1)](https://user-images.githubusercontent.com/56890879/152362281-9065dfec-2e47-4a7a-8d15-e1356836e820.png)

## Parts Explained:
[Flight Controller](https://fusion.engineering/flight-controllers-explained-for-everyone/)


### RC Communication Protocols 
-------------------------------
RC communication protocol is way of communication between the reciever to transimiter/trasmiter to the controller(FC in our case). The ability of the commponents to be
able to commuinicate through a common protocol is a must, otherwise they won't be able to work with each other. 

#### There are two types of RC protocols:
* TX protocol
Communication between (Tx) the radio transmitter and radio reciever

* RX protocol 
communication between (RX) the radio reciver and (flight) controller


#### Common Rx (radio reciever & FC) Transm protocol communication
#### PWM
PWM stands for Puls width modulation, is the analog signal interface. PWM uses separate wires for each channel. PWM is the only protocol capable of direct 
communication to servo/ESC since the signals won't have to be interperted to the servos/ESCs. Pulse-width-modulation is a process by which signals are sent down the
signal line from the receiver to the device that to which communication is needed. The signal forms “pulses” by sending precicely separated bursts of signal, the
distance between which will give different commands to the servos or speed controllers.  With a servo, the separation of the signal will determine the angle that the 
servo is supposed to have, and for a speed controller, it tells it the speed at which it’s supposed to spin the motor. The downside of using PWM is it requires a 
seperate wire for each channel. It's extra weight for the drone, and looks messy.

#### PPM/CPPM
PPM stands for “pulse position modulation”. PPM iterates the signal through all channels and sends the signals to the specific routes and distinations which gives it 
the capablity of using only one wire to do it. The reciever and FC have to know how many channels to expect, so they know how to read the signal by iterating the 
signal through the expected number of channels and sending the signal to each specific channel. The flight controller then reads each of the signals in sequence, and 
then reads the pulse width of each channel, setting that as the value for the channel. The signals are still analog but are transmitted in a nearly digital way.

A PPM signal is basically a series of PWM signals sent one after another on the same wire, and modulated differently. The advantage of PPM over PWM is that only one  
single wire is needed for several channels. So typically, you would only need to connect the ground, power and signalwires for up to 8 channels.As the channel values 
don’t arrive at the same time, it’s not as accurate or jitter-free as serial communications.

##### Serial Protocol
A serial protocol is a digital loss-less protocol that uses only 3 wires (signal, power, ground) for multiple channels. Unlike PPM which is a signal in time domain, serial protocols are completely digital which means they are made up of a bunch of one’s and zero’s.

Serial protocols require a serial port on the flight controller known as UART.

##### Analog vs Digital communication protocol
One downside of analog signals like PPM and PWM is that the signal is potentially “lossy.” Occasionally in transmission, data can be false or erroneous due to 
thousands of potential interferences. When this happens in an analog signal, there’s zero way for the flight controller to know that a particular value has error. As a 
result, the flight controller is responsible for executing what is called a “3 frame rolling average.” Essentially, what this provides is a “smoothing” factor over 
values given from the receiver such that any erroneous values don’t affect performance of the machine is extremely adverse ways (i.e. temporarily cut throttle, or turn 
one motor all the way up for a split second).

#### S.BUS
S.BUS, the S standing for Serial can supports up to 16 channels using only one signal wire. SBUS signal should be connected to the RX pin of an UART.S.BUS uses the 
UART communication ports to send the one-way SBUS signal from the receiver to the flight controller. UART traditionally has 5v, gnd, rx and tx, but S.BUS only requires 
the ability to send the signal from the receiver to the flight controller, so many flight controllers now are creating a dedicated UART port that only has input, 
simplifying the connection process for the user  hooking up the receivers.As a result of this, like with PPM, S.BUS requires only one cable running from the receiver to the flight controller, and across this all channels will be transported.

In addition, because of a digital signal, we have the ability to take advantage of what are called “checksums.” These are clever little pieces of information that are 
sent along with each message to the receiver that tell it whether or not the value received had an error state. The analog signals from PPM have to be accepted by the 
flight controller because there is no possibility for checksum with analog signals.As a result, the SBUS connection doesn’t require a 3 frame average, bringing its 
response time down to around 9ms, while PPM stays in the 50+ range. In in addition, RC 
Smoothing is not required because there is little to no error.


- RX and TX protocols may use a common communication protocol, or they might use two different protocols

![Tx-RX-communication-protocol-visual](https://user-images.githubusercontent.com/56890879/159382147-fa7824d7-28be-4d57-9c04-29e66ac1e0ae.jpg)
Image from: [OscarLiang](https://oscarliang.com/rc-protocols/)

Sources:
[Paul Nurk Kala](http://paulnurkkala.com/pwmppms-bus/)
[OscarLiang](https://oscarliang.com/rc-protocols/)


## Safety protocols

safety glasses will be worn all the time specially while flying in close distance and lower altitude. We thought of giving the drone an obsticale avoiding functionality to 
improve it's saftey of itself and its surroundings. Another point that will be taken into consideratin is clearing the flight and take off space and flying in hazardous 
situations must be avoided.

## Initial design (pencil and paper, CAD, etc.)
Rough sketch of how the drone will look. There will be surly more details and changes init but the this is the basic shape.

![drone initial design](https://user-images.githubusercontent.com/56890879/153009067-8bd03551-53f3-48ce-b433-81b0a0c2a3e0.png)
## Deadlines

![drone-deadlines](https://user-images.githubusercontent.com/56890879/156189351-133df5f4-e2e4-4c17-a8d2-8cc43b7c152e.png)


## CAD DESIGNS
![0 0](https://user-images.githubusercontent.com/56890879/168860504-95238607-ce14-490f-8ed7-615d432de739.png)
![initailDesign](https://user-images.githubusercontent.com/56890879/168860674-976942de-8d58-48fc-878f-96b31076e8b7.png)
![2 1](https://user-images.githubusercontent.com/56890879/168860538-5510cb27-4599-44f5-9d88-0bc60edf028d.png)
![2 2](https://user-images.githubusercontent.com/56890879/168860550-ab69ccc9-fa8a-40bd-8117-e277b07cda1a.png)
![3 0](https://user-images.githubusercontent.com/56890879/168860558-af61d8d5-bb60-48f6-845f-d33f6a57abf2.png)
![4 0a](https://user-images.githubusercontent.com/56890879/168860587-ed27d341-c6dd-4bbb-ad02-b83631d39e77.png)

## PICTURES


![Screenshot 2022-05-27 124354](https://user-images.githubusercontent.com/56890879/170743406-c24dcf37-1c21-4d3f-b56d-86fba274e2c8.png)

![Screenshot 2022-05-27 124419](https://user-images.githubusercontent.com/56890879/170743429-105249be-d564-4e95-9cb0-d4a4dec6c5fd.png)
![Screenshot 2022-05-27 124439](https://user-images.githubusercontent.com/56890879/170743438-8b19f92d-3521-413c-a2d6-7ecb7848fa21.png)
![Screenshot 2022-05-27 124455](https://user-images.githubusercontent.com/56890879/170743442-5a80f8bd-504b-4b9e-85ed-e5c5db9b77da.png)
![Screenshot 2022-05-27 124509](https://user-images.githubusercontent.com/56890879/170743449-5d689c63-eec5-4ffc-a2c8-d6787171ed57.png)
![Screenshot 2022-05-27 124523](https://user-images.githubusercontent.com/56890879/170743458-396c5a54-e68f-4044-b244-392421f2512b.png)
![Screenshot 2022-05-27 124523](https://user-images.githubusercontent.com/56890879/170743463-ec4c196a-cbd4-4737-8b6a-a948f8afdb29.png)
![Screenshot 2022-05-27 124537](https://user-images.githubusercontent.com/56890879/170743471-9e1166ec-7978-42f3-94f6-62326af997d0.png)
![Screenshot 2022-05-27 124612](https://user-images.githubusercontent.com/56890879/170743476-0caf8736-64f8-481c-a9fd-2b51ba35eaa7.png)
![Screenshot 2022-05-27 124624](https://user-images.githubusercontent.com/56890879/170743487-faa97b35-9864-48b7-ba08-d5a774fb7ee1.png)
![Screenshot 2022-05-27 124637](https://user-images.githubusercontent.com/56890879/170743495-a77ee6ed-4381-4c97-af8a-f7cb843daa70.png)

![Screenshot 2022-05-27 124649](https://user-images.githubusercontent.com/56890879/170743503-becb6dae-2ffb-415c-87ac-f82663e3abfe.png)
![Screenshot 2022-05-27 124703](https://user-images.githubusercontent.com/56890879/170743504-9799aca0-8eca-40f3-b419-1b2e7b05ff6f.png)


## SUGGESTIONS
Use this type of ESC instead of the ones we had because it does exactly what those other ESCs will do and it will save you a lot of space and weight.
[LINK](https://www.banggood.com/Eachine-Wizard-X220S-FPV-Racer-RC-Drone-Spare-Part-4-in-1-30A-ESC-BLHeli_S-2-5S-Dshot600-p-1172948.html?utm_source=googleshopping&utm_medium=cpc_organic&gmcCountry=US&utm_content=minha&utm_campaign=minha-us-pc&currency=USD&cur_warehouse=CN&createTmp=1&utm_source=googleshopping&utm_medium=cpc_us&utm_content=nolan&utm_campaign=aceng-pla-usa-all4-20220402&ad_id=513043829882&gclid=CjwKCAjwj42UBhAAEiwACIhADiSV8H7zgwVzK7E-7L0V68syqlYBK65fGoz2y2oISFr4y5m8q1ImRhoCBToQAvD_BwE&scrlybrkr=0ac48c88)

### LIPO BATTERY USAGE
It is crucial for anyone whose just getting started into using lipo battries to know the saftey requirements. It strongly suggest that you go through a couple articles 
and read about the saftey measuerments and how to maintain a lipo battery. Lipo battries are not like the regular double A batteries that once you're done with them 
you toss them away. You will have to regualte the volatage it has according to your needs and usage. You'll have to know how much current you're gonna need so that
you purchase a lipo accordingly because if you overuse it - it's going to end up ugly for you. Down this paragraph is a pucture of the first lipo batteries we were 
using and apparantly they went bad. One of the cells does not work at all and the entire thing looks squishy. If it's used in such condition - you shouldn't be 
surprised if it explodes or catches fire. I strongly recommed you go through [this](https://www.thedronegirl.com/2015/02/07/lipo-battery/) artcile and read through all 
the points carefully before using a lipo.

![Screenshot 2022-05-27 124715](https://user-images.githubusercontent.com/56890879/170743512-adb9e84e-d168-4519-8951-ed73c237569f.png)

### ESC
The ESCs we used for our drone works really well and is easy to use. The only downside to it is it takes a lot of space and adds to the overall weight of the drone 
compared to a 4 in 1 ESC for a quadcopter. That would make your life much easier. The frame will not look as messey. 

### Capacitor
It is always a good idea to use a capacitor to regulate the amount of volatage going in to the compartments. Capacitor will prevent power surge or popwer defeciency. 
It stores the energy if there is a voltage spike and releases it wehen there is a power defeciency in the circuit. It would prevent the drone from being too shakey. I 
would mount a relitavley high capacitor on my power distributor board so that all the parts get the exact intended amount of voltage.

### Saftey
Henry...?

# [Back to the Top](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#pi-in-the-sky)
