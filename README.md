# CREATE 2021-2022 ReadMe

This ReadMe file uses Markdown formating.  Helpful cheat sheet is available here: 	[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

## Hardware Dependencies
This project is very hardware oriented, and once we describe each item it will show how intuitive the hole system is.

1. We use a D/D Blower w/ Motor, 208-230/460 V. For our desired system we need a reliable and robust blower/motor
combination. This blower has an 11-inch turbine which is large enough to not get jammed or
clogged by small paper shreds. The motor that comes with this setup is a 1 horsepower 3
phase electric motor that can spin upwards of 3500 RPM. With our system, we plan on using
4 inches ducting for the inlet and the exhaust side and with a 4-inch outlet, this blower can
push nearly 560 CFM which should be plenty for our application
![Motor](https://user-images.githubusercontent.com/94560718/143474750-30389b5a-9629-48b6-986f-c4caeea1bac9.jpeg)

2. We use a 3 Phase 30A 3.7KW Maintained Self Lock On/Off Power Pushbutton Switch. It has ideal specifications to deal with the power needed by the motor and has the perfect 
functionality we are looking for our system. Once pressed On it maintains like that until we press the Off button.
![Switch](https://user-images.githubusercontent.com/94560718/143475406-b4c95b56-3b19-47a3-9a57-f8a15fa55bb0.jpg)

3.We use a MODEL GN3442 GAYLORD COVER because the goal of the system designed in this project is to get the shredded paper
automatically into the big brown box provided by the mailing service company. In order to do
that, we require this component because the whole system works around a motor/blower
that creates wind gusts that would make kind of sloppy the whole movement of the paper.
This device provides a specific and convenient solution, covering the box and just letting the
tube with the shredded paper have access to it. This way, we use the cover until the box is
full and then easily remove it to get the shredded paper out.

![gaylordCover](https://user-images.githubusercontent.com/94560718/143475968-44d21cc6-298b-4956-810a-f37e89c8d367.png)

4.We use a 14/3 NM-B WG Romex Wire/Cable due to the fact that we are using a 3 phase motor/blower. This ware has three conductors and a neutral wire. The function of neutral wire in 3 phase 4 wire system is to serve as a return wire for general domestic supply system. The neutral is paired to each of the single phase load. The potential of the neutral point can be very well understood from the following Figure. The total neutral current is the vector sum of the three line currents. Under balanced conditions the vector sum is zero and therefore, the neutral current is zero

![purpose-of-neutral-wire-in-three-pahse](https://user-images.githubusercontent.com/94560718/143479185-fb4dca6e-e3ff-4286-8036-4c1b1f70b899.png)
![Wiring](https://user-images.githubusercontent.com/94560718/143479221-ade46860-dc00-447b-940e-9b7b327516f5.jpg)

5.The plug in is adapted to the needs of the system and is a 20A, 3 pahse and 4 wiring black and white plug in with a capacity of 125/250V.

![plugIn](https://user-images.githubusercontent.com/94560718/143480612-138028ed-a5f9-469e-87b5-fd4f03b79a28.jpg)


6.To connect the box, the blower and the gaylord we used 4 inch galvanized steel pipes.
![Pipes](https://user-images.githubusercontent.com/94560718/163867243-9fde9999-bca2-4b5b-8ec2-2041a2872517.jpg)


## Software Dependencies
To connect the different components of the system, we use 3D parts modeled by us in a customized way for the different needs of the project. We have used 3 parts. The first one connects the motor with the pipe that goes to the gaylord. The second one connects the box where the paper falls with the pipe that connects to the motor. The third one is on the other side of the tubing and connects to the motor.


## Steps Required to Replicate your Work. List the steps required to replicate your work
1. Wire the motor to be in low voltage mode by connecting T7 and T1 in line 1, T8 and T2 in line 2 and T9 and T3 in line 3.
2. Wire the different components together, the plug in with the switch, and the switch with the motor.
3. Set up the pipeline system between the motor and the two bins, the one under the shredder and the one that will leave the building.

![SystemOverview](https://user-images.githubusercontent.com/94560718/143473394-fbb5a34b-46f3-4d57-92eb-e5e778e8988c.png)

![System - Front](https://user-images.githubusercontent.com/94560718/143942950-51944412-afff-4cc4-b684-ce5811069d16.jpg)
![System - Rear](https://user-images.githubusercontent.com/94560718/143942965-f8466e03-7335-4348-9013-0650754949d0.jpg)


## Instruction Video: 

https://youtu.be/Mo4UCGreJuw
