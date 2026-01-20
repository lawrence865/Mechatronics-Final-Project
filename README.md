# Mechatronics-Final-Project

OVERVIEW:
In billiards or pool games you must reset the table after each round. Currently, this is a fully manual process, a player must sort them, re-rack them and then   
reset them before play can resume. This project is a robotic/mechatronic system that automates the sorting and resetting of pool balls on a custom made mini portable 
pool table. The system will be capable of identifying pool balls by color, sorting them in play order, and placing them into the traditional triangular arrangement on 
the table. The end goal is to create a device that can manage sorting and resetting a game of pool with no human intervention while still being portable and playable.
The table uses a 3 axis gantry system with a claw to grab and move balls to desired locations for sorting, organizing, and re-racking. 

PARTS:
- A fully customized table shrinken in proportions to regular pool tables with a collection ramp system built beneath the table, made of wood
- A Gantry system with tracks in the X, Y, Z direction driven by motors, with motor encoders
- A claw with color sensor, bumper sensor, and controllor mounted on its cases, used to pick up and release balls into its proper location in the automated process
- A ball collection ramp with doors above the table tjat stores all balls until it is ready for re-racking

PROCESS (MY ROLE):
The Claw: 
Designed and 3D modelled SolidWorks parts and assemblies for the claw subsystem. This includes the front case, back case, and the claw arms. 
Used c++ and VEX IDD to code the functions that allowed the claw to run on unknown parameters that allowed for easier integration and a more organized structure. Functions include:
- Opening and closing function
- Applying constant torque
- Sensor input Functions
- Setting the claw to specific angles
- Helper function that preformed mathematical processing used for sorting

The table and ramp: 
I created the design and SolidWorks CAD for the ramp and attached it to the table in an assembly. I was also a part of the manufacturing process of the table. 
This includes:
- Using the drill press to drill the pockets in the table
- Using hand drills and clamps to drill holes for fastener
- Using the mitre saw to cut planks into useable pieces
- Using electrical hand sander for finishing touches
