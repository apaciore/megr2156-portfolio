# A4 – Motor Mount

## Objective

The objective of this assignment is to design a motor mount to be attached to a rigid wall, with the intention of holding a Brushed 24V DC Gear Motor 3.6Kg.cm/46RPM w/ 99.5:1 Planetary Gearbox. The goal is to design for yield strength as well as maximum deflection, including selecting an appropriate cross sectional area and material (between three options), and safety factor should be 3. Alongside this, we are also tasked with researching different types of motor mounts, and showing the process of modeling the mount in CAD. 

## Feature 1 (includes sketch)

![figure1](Screenshot%202026-09-16%20220927.png)

PLA was the material that I picked out of the three. I chose to make the length and width dimensions of feature 1 30mm, since the gearbox has a diameter of 28mm according to the reference, so this would be enough space to house the motor. I utilized the free body diagram to create a moment calculation, which I used as a variable in my stress formula, which I rearranged to find my height of feature 1, 6.708mm. 

## Feature 2 (includes sketch)

![figure2](Screenshot%202026-09-16%20221123.png)

I completed a very similar calculation to find the same height/thickness of feature 2 using stress equations. When I solved for the same value using the deflection equations, I got a smaller diameter of 5.386mm, so I chose the larger of the two to ensure that feature 2 is thick enough for the applied force. 

## Isometric Sketch

After determining the minimum thickness of features 1 and 2, I drew up an isometric sketch for the motor mount. This helped a lot with easily reading and understanding the dimensions when building the CAD model in the next step.
![iso](Screenshot%202026-09-16%20221158.png)

## CAD Model (Parametric)

I first sketched the length and base of feature 1 to size, and then extruded the sketch to my height that I solved for, 6.708mm.

![base](Screenshot%202026-09-16%20210604.png)

I then created 3 radial cut extrusions, the largest being 28mm diameter, the size of the gearbox, for 2mm of depth. I then did the second extrusion another 2mm down from there at a diameter of 18mm, and then the last one the rest of the way through at 6mm diameter.

![basewholes](Screenshot%202026-09-16%20211712.png)


Then I sketched feature 2 to my specified dimensions and extruded it across the base. 

![feat1and2](Screenshot%202026-09-16%20212215.png)

From there, I was able to create my four holes in feature 2, used to screw in the mount. I two 3.4mm circles on the bottom half of the plate, and mirrored them two create two more on the top half, so all four were evenly spaced across the four quadrants of the surface. Lastly, I cut extruded these holes all the way through so the mount can be screwed in place.

![feat2holes](Screenshot%202026-09-16%20221943.png)




