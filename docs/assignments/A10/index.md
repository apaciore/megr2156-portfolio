# A10 – Lead Screw Translating System

## Objective
The objective of this assignment is to utilize a lead screw in order to design a tensile tester, which is a device used to measure how materials respond to uniaxial tension. The goal is to design a tester that is capable of 2 kN axial tensile load and a crosshead speed from 1-50 mm/min. The system is to be purely mechanical, have a manageable height- ideally used as a tabletop device, 18 in leadscrew minimum, and safety factor of 4. 

## Design
### Hand Calculation

![calc1](Screenshot%202026-11-23%20140904.png)

The first thing to do on the list is to solve for the minimum diameter of the lead screws, so that way we can select the correct lead screw part. Using the stress equation and rearranging the variables, I was able to find the minimum diameter to be 4.51 mm or 0.1776 in. The lead screw that was selected as a result was the 1/4 in one, since this is the closest to the minimum diameter solved for.
The next thing to find was the range of rotational speed of the screw, utilizing the linear speed range given and the lead screw pitch. The pitch implied from the 1/4 lead screw selection is 1/16 in.

![calc2](Screenshot%202026-11-23%20140921.png)

The final calculation involving the lead screw is the max torque that will be applied resulting from the 2kN force. My max torque was found to be 0.6786 N-m per screw. As a result of these calculations, the corresponding lead screw was selected- [Link for Lead Screw](https://www.mcmaster.com/99030A981/).

![calc3](Screenshot%202026-11-23%20141111.png)

After the lead screw had been selected, a nut and flange had to be selected for it to pair with. Using thread bending stress analysis, I found the max stress to be 101.05 MPa, which confirmed that bronze could be the material used for the nut. Assuming the length of the nut to be 5/8 in, and matching it to the pitch of the lead screw thread, the following nut was selected- [Link for Selected Nut](https://www.mcmaster.com/95072A881/).
This nut has an external thread of 9/16-18, and the corresponding flange was selected- [Link for Selected Flange](https://www.mcmaster.com/95082A641/).

![calc4](Screenshot%202026-11-23%20141125.png)

The last thing to design before modeling the part in CAD was the crosshead. Utilizing the internet, I found a sufficient base/width for a crosshead, 50mm, and the length of the crosshead that follows the base, 300mm. Using these values as well as strength requirements like the load presented, yield strength, and max deflection, I rearranged the stress equation to solve for the minimum height of the crosshead which was about 14 mm.

![calc5](Screenshot%202026-11-23%20140945.png)

Pictured above is my sketch of the crosshead design with the necessary dimensions.

### CAD

![cad1](Screenshot%202026-11-23%20125316.png)

The first step in the CAD process was to create a parametric table with with the decided length, base, and calculated height dimensions. From this, I made a rectangle at this length and base, and extruded it to this height. 

![cad2](Screenshot%202026-11-23%20125559.png)

The next step was creating the two holes for the lead screws. I sketched the two circles at the 1/4 in diameter of the lead screws, and extruded them through so that way the lead screws can pass through the crosshead. 

![cad3](Screenshot%202026-11-23%20131013.png)

Following this, I was able to sketch the bolt holes and extrude them but not all the way through, in order to fasten the flanges. 

![cad4](Screenshot%202026-11-23%20140257.png)

Now, it was time to assemble the other parts I selected to the crosshead I designed. 



## Communicate

