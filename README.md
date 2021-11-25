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

5.The plug in is adapted to the needs of the system and is a 

## Software Dependencies
For the moment we are not using any software dependencies, later on we might include a sensor to detect when to run the whole system, but for now no software has been used.

## Steps Required to Replicate your Work. List the steps required to replicate your work
1. Wire the motor to be in low voltage mode by connecting T7 and T1 in line 1, T8 and T2 in line 2 and T9 and T3 in line 3.
2. Wire the different components together, the plug in with the switch and the switch with the motor.
3. Set up the pipeline system between the motor and the two bins, the one under the shredder and the one that will leave the building.

![SystemOverview](https://user-images.githubusercontent.com/94560718/143473394-fbb5a34b-46f3-4d57-92eb-e5e778e8988c.png)

## Instruction Video: 
Create a short video that shows the steps necessary to set-up your environment and replicate
the work that you have completed. If necessary, separate these steps into multiple short videos. Post on
YouTube and include the links on your GitHub repository
