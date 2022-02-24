# Pi-in-the-sky


Table of Contents:
* [CONSTRAINS](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#constraints)
* [IDEAS](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#ideas)
* [SOLUTION](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#solution)
* [COMPONENTS](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#components)
* [RESOURCES](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#resources)
* [SAFETY PROTOCOLS](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#safety-protocols)
* [WEEKLY PROGRESS]()



## Planning 
### Goal
We have to make some sort of electronic creation using a raspberry pi that flies into the air and records data when it is at its apex height.data.

We want to make a drone using a pi that flies into the air and has a compartment that can drop things. aLthough it sounds simple, we want the drone to have a specific 
function. It should drop seeds to help the environment or have extra long battery life in order to be able to deliver things.

### Constraints
* The idea of a drone with a controller relies on radio communication with the drone. We have no idea how that works so we have to learn about it and overcome any obstacles we may encounter when using the radio communication and the raspberry pie.
Drones are very hard to make and if we want to have a special drone, it will take lots of tests and therefore time. This project will take tons of research to fully complete. We will have to specifically research each aspect of the project and plan out the physics of it. 
Live streaming of 360 cameras with VR is another obstacle to be overcomed and needs a significant amount of research and analysis

### Ideas
#### Gravity Sensor vs. Accelerometer (research):

________________________________________________________________________________________________

#### Very Rough Sketches:

https://www.youtube.com/watch?v=LVoPGlNvHhw   (Example of how our model will look like

#### Very Rough Designs 
https://droneomega.com/drone-motor-essentials/

https://www.learnrobotics.org/blog/3d-printed-drones-thingiverse/

### Solution


To be added...
________________________________________________________________________________________________

### SPICY PART:

Gesture control over the drone. We are thinking about using accelerometers or medical chips to match the movement of our hand to the movement of the drone.
We may want to control the drone using just the movment of our hand. This is a very rough idea and we will work on it once we know we can make a working drone. 

Another idea is to use gravity sensor for the hand gesture flight control, but we do not have prior knowledge of how this system of flight in drones work. We will need to dig 
deep into that. The concerning part for the moment is figuring out the exact boards and chips we will use and also the communication between the drone and your hand.

### Components 

Brushless Motor: 	  [EA CHINE 2300KV](https://www.eachine.com/Eachine-2205-MN2205-2300KV-2-4S-Motor-For-Eachine-Wizard-X220-X210-250-280-FPV-Racing-Frame-p-642.html)      
KV: 2300
RPM = kv*volts


[Speed Controller Model](https://www.amazon.com/RC-Brushless-Electric-Controller-bullet/dp/B071GRSFBD/ref=as_li_ss_tl?ie=UTF8&qid=1549129228&sr=8-5&keywords=esc+30a&linkCode=sl1&tag=howto045-20&linkId=e1a4f6875272396432e2554f55ee0113&language=en_US)

[Radio receiver](https://hobbyking.com/en_us/turnigy-tgy-i4x-mode-2-afhds-afhds-2a-switchable-4ch-transmitter-receiver.html)

[Transmitter](https://www.horizonhobby.com/product/ar636b-dsmx-6-channel-as3x-sport-receiver/SPMAR636B.html) 

[Fight controller](https://www.giogird.com/product/30-5x30-5mm-jhemcu-f7bt-dual-gyro-f722-f7-2-6s-flight-controller-aio-osd-5v-8v-bec-support-bluetooth-dji-air-unit-for-rc-drone/)   

Battery:            Lipo

[Camera](https://www.google.com/shopping/product/1?q=wifi+module+for+drones&prds=epd:3335392841495737051,eto:3335392841495737051_0,pid:3335392841495737051&sa=X&ved=0ahUKEwiOivyMgYf2AhXAl3IEHZFsCxgQ9pwGCAk)

[Props](https://www.google.com/shopping/product/1?q=propellers+drone&bih=937&biw=1920&rlz=1C1GCEU_enUS969US970&hl=en&prds=eto:2152026255289366735_1,pid:2152026255289366735)




________________________________________________________________________________________________
# [Back to the TOP](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#pi-in-the-sky)

## Resources

* https://www.youtube.com/watch?v=bCEiOnuODac
* https://howtomechatronics.com/tutorials/arduino/arduino-brushless-motor-control-tutorial-esc-bldc/
* https://www.google.com/search?q=blheli_s+esc&rlz=1C1GCEU_enUS970US970&source=lnms&tbm=isch&sa=X&ved=2ahUKEwijx_6QtvX1AhVZgnIEHZ1CClkQ_AUoAXoECAEQAw&biw=1924&bih=955&dpr=1#imgrc=0RJoredFywCU-M


Drone motor calculator 
https://www.omnicalculator.com/other/drone-motor
Info on Weight Ratio
https://top-10-drones.com/choose-motor-propeller-quadcopter/

Motor specifications
https://www.getfpv.com/dys-samguk-series-wei-2207-2300kv-motor.html

2300kv
https://ae01.alicdn.com/kf/HTB1Wqs_gPqhSKJjSspnxh779XXak.jpeg


Motor model: SAMGUK serious KV 2300


![pasted image 0](https://user-images.githubusercontent.com/56890879/152362260-7c9233a2-e19b-481a-9829-89f53286319e.png)
![pasted image 0 (1)](https://user-images.githubusercontent.com/56890879/152362281-9065dfec-2e47-4a7a-8d15-e1356836e820.png)

### Parts Explained:
[Flight Controller](https://fusion.engineering/flight-controllers-explained-for-everyone/)


## Safety protocols
safety glasses will be worn all the time specially while flying in close distance and lower altitude. We thought of giving the drone an obsticale avoiding functionality to 
improve it's saftey of itself and its surroundings. Another point that will be taken into consideratin is clearing the flight and take off space and flying in hazardous 
situations must be avoided.

## Initial design (pencil and paper, CAD, etc.)
Rough sketch of how the drone will look. There will be surly more details and changes init but the this is the basic shape.

![drone initial design](https://user-images.githubusercontent.com/56890879/153009067-8bd03551-53f3-48ce-b433-81b0a0c2a3e0.png)

## Weekly Progress

# [Back to the TOP](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#pi-in-the-sky)
