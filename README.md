# Robot Sumo

## Project Overview

Robot Sumo is a combat robotic oriented sport where autonomous robots fight to push each other out of a circular arena. From October 2025 to March 2026, five students from Team Kami designed and built a 500 kg autonomous robot to compete at Georgia Tech's In-House Competition, Jacket Racket. As Team Kami's mechanical sub-team member, I was responsible for designing our robot's chassis, metal base plate, and arm.

## Project Goals

➣ Build an autonomous robot within design constraints    
➣ Design a robot that is easy to assemble and disassemble  
➣ Maintain a low center of gravity using a heavy baseplate   
➣ Utilize 3D printing tools to build chassis  
➣ Include rotating arms with flags


# Timeline

## Kami V4.0

<div style="display: flex; gap 10px;">
  <img src="https://github.com/andreaxlan/RobotSumo/blob/e15814807f15c894c832ecc52b4527596f265548/Photos/V4.0.png" width="400">
  <img src="https://github.com/andreaxlan/RobotSumo/blob/e1022f421a1cb862627559c27f78c3465e2bdb24/Photos/V4.0%20EXPLODED.png" width="600">
</div>

### 2.20.2026

All CAD parts of Kami V4.0 are complete and assembled in SOLIDWORKS! 



### 1.20.2026

We decided to mount the PCB to the top of the robot using M3 standoffs. After evaluating the minimum space required for the arms to retract into the 10 x 10 cm bounding box, I determined the maximum size of the PCB to be 75 x 49 mm. The SOLIDWORKS evaluate feature estimated the mass of the complete assembly to be approximately 410 g.

### 1.18.2026

The initial chassis of Kami V4.0 was completed. The line sensors were moved forward, the orientation of sensors was readjusted to fan outwards, and the angle/posiiton of the servo motors was determined. 

## Kami V3.0 

<div style="display: flex; gap 10px;">
  <img src="https://github.com/andreaxlan/RobotSumo/blob/8b14877b22c821ebc48d38b5ade597927aa1d290/Photos/V3.0.png?raw=true" width="400">
  <img src="https://github.com/andreaxlan/RobotSumo/blob/100226e4ce28deda03770038b2d2b2927b6cf8ef/Photos/V3.0%20TOP%20PLATE.png" width="450">
<div>


  
### 11.20.2025

We had a mechanical design review today and recieved the following recommendations:  
<br>
➣ Current set up of sensors is redundant, sensors should fan outwards to maximize range  
➣ Underside of back plate shouldn't be a 90 degree angle since opponent blades can slide underneath  
➣ Chassis needs to be shorter so robot blade can hang  
➣ Line sensor needs to move forward to prevent delayed sensor response  
➣ Parts should be assembled using screws   

### 11.13.2025

The physical robot was fully assembled for the first time with electronics! Kami V3.0 includes minor adjustments of parts. We tested separating the top plate from the base plate and adding a lip on the connectors to prevent sliding in horizontal and vertical directions. While motion was restricted in one direction, friction alone was unable to prevent parts from disengaging in collision. In addition, tolerancing issues persisted with the distance sensors which was temporarily fixed with tape so programming could test the robot.

## Kami V2.0

<img src="https://github.com/andreaxlan/RobotSumo/blob/994e723dd7dec08882a990ae7427d056e11128f2/Photos/V2.0.png" width="400">

### 11.1.2025

Kami V2.0 is split into three parts: chassis, base plate, and top plate. The top plate serves as a mounting plate for the PCB and features a honey comb pattern for wires to pass through. I noticed electronic parts would be difficult to assemble, so the chassis and top plate became separate parts held by friction. Line sensor holes were added to the bottom and distance sensor holes were added to the front. The base plate was CADed separately by another mechanical sub-team member, so this model does not include a separate base plate.   
<br>
After 3D printing Kami V2.0, we discovered tolerancing issues with the distance sensors which would require adjusting the CAD model and reprinting.

## Kami V1.0 

<img src="https://github.com/andreaxlan/RobotSumo/blob/f5a8ca1e35a62731af90808d16fc0f3c174d1ab0/Photos/V1.0.png" width="400">

### 10.2.2025

The first few weeks of Robot Sumo were dedicated to new member training. Mechanical sub-team members recieved basic SOLIDWORKS training and were given general design guidelines. After meeting my teammates, our team weighed pros and cons between several concept designs and decided to build a robot with two flag arms. The purpose of the flags is to extend the robot so that the sensors of opposing robots will be misguided to aim for the flags instead of our robot chassis.   
<br>
Kami V1.0 is a mock assembly of our robot. I wanted to figure out the general shape of our robot and the parts we would be using before fully committing to a complex CAD design.
