# Pi-in-the-sky


Table of Contents:
* [PLANNING](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#planning)
* [RESOURCES](https://github.com/afaqirz67/Pi-in-the-sky/blob/main/README.md#recourse)


## Planning

#### Problem:
We have to make some sort of electronic creation using a raspberry pi that flies into the air and records when it is at its apex height. It must also record some extra data.

#### General idea:
Me and Asad want to make a drone using a pi that flies into the air and has a compartment that can drop things. aLthough it sounds simple, we want the drone to have a specific function. It should drop seeds to help the environment or have extra long battery life in order to be able to deliver things.

#### Main anticipated problems:
* The idea of a drone with a controller relies on radio communication with the drone. We have no idea how that works so we have to learn about it and overcome any obstacles we may encounter when using the radio communication and the raspberry pie.
Drones are very hard to make and if we want to have a special drone, it will take lots of tests and therefore time. This project will take tons of research to fully complete. We will have to specifically research each aspect of the project and plan out the physics of it. 
Live streaming of 360 cameras with VR is another obstacle to be overcomed and needs a significant amount of research and analysis.


### Gravity Sensor vs. Accelerometer (research):

________________________________________________________________________________________________

#### Very Rough Sketches:

https://www.youtube.com/watch?v=LVoPGlNvHhw   (Example of how our model will look like

#### Very Rough Designs 
https://droneomega.com/drone-motor-essentials/

https://www.learnrobotics.org/blog/3d-printed-drones-thingiverse/

________________________________________________________________________________________________

### Components 

Brushless Motor: 	  [EA CHINE 2300KV](https://www.eachine.com/Eachine-2205-MN2205-2300KV-2-4S-Motor-For-Eachine-Wizard-X220-X210-250-280-FPV-Racing-Frame-p-642.html)      
KV: 2300
RPM = kv*volts


Speed Controller Model: [EFM8BB-20A-4S-V13](https://www.google.com/search?q=EFM8BB-20A-4S-V13&rlz=1C1GCEU_enUS970US970&source=lnms&tbm=isch&sa=X&ved=2ahUKEwivi-305-P1AhWTqXIEHe2bCiUQ_AUoAXoECAEQAw&biw=1924&bih=959&dpr=1)

Radio Controller:  	[TURNIGY TGY - i4X](https://hobbyking.com/en_us/turnigy-tgy-i4x-mode-2-afhds-afhds-2a-switchable-4ch-transmitter-receiver.html)

Transmitter: 	      [Spektrum AR636B 6CH SPORT RECEIVER](https://www.horizonhobby.com/product/ar636b-dsmx-6-channel-as3x-sport-receiver/SPMAR636B.html) 

Fight controller: 

Battery:

Camera:

Props:

Frame:           will be 3d printed



________________________________________________________________________________________________


## Resourses


#### Online Info:

* https://www.youtube.com/watch?v=bCEiOnuODac
* https://howtomechatronics.com/tutorials/arduino/arduino-brushless-motor-control-tutorial-esc-bldc/


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

________________________________________________________________________________________________

### SPICY PART:

Gesture control over the drone. We are thinking about using accelerometers or medical chips to match the movement of our hand to the movement of the drone.
We may want to control the drone using just the movment of our hand. This is a very rough idea and we will work on it once we know we can make a working drone. 

