# A8 – Gears

## Objective
The objective of this assignment is to design a gearbox that can be assembled and disassembled. The input and output shafts are to be sized and the strength to be calculated for. The gearbox housing must have proper clearance and fastening. We need to model and design this gearbox parametrically in CAD, and make engineering drawings for all the parts used.


## Hand Calculations and Design Specs

![handcalc1](%202026-11-02 133008.png)

I chose to opt for a simple design, where the two halves of the gearbox snap fit to enclose the gears. Because the gears have a diameter of 0.402 in and 1.027 in each. To allow adequate clearance and space for the user to slide the gears into the box, I decided to make the box 2.5 in width and 2 in length. The size of the journal bearings require the walls to be 0.25 in thick so that way the shaft is able to stick out of the gearbox adequately. To ensure that the gears can spin freely, a total depth of 1 in made sense- total being the depth with the face snapped on. 

## CAD Modeling

I sketched my box to my decided length and width, and extruded it to a depth of 0.9 in, leaving 0.1 in for the width of my other half of the gearbox.

I sketched another rectangle onto the face of this prism, 0.25 in inward from all sides, and then cut extruded the shape to 0.25 in away from the back of the box. This create a shell with a thickness of .25 on all sides except the front face, which is left completely open to insert the gears.

I sketched the four pin holes at the center of the four corners of the shell on the side with the open face. The holes were sketched to a diameter of 1/8 in as that would be the size of snap fitting pins used, and I cut extruded these circles to a depth of 0.25 in. 

I sketched circles with diameters of the input and output shaft on the back face, and cut extruded all the way through to create the holes for the input and output shafts.

I then moved onto the other side of the gearbox assembly. I sketched the length and width the same as the previous part, and extruded it to the remaining 0.1 in. I then drew the 4 pin circles in the same position as previous, but extruded them to a length of 0.25 in rather than cut extruding and making holes. This was all the steps for the second half of the gearbox.

I then modeled the two different shafts in CAD, one at 0.125 in diameter and the other at 0.25 in diameter, and both 1 in in length.

All of the parts were then inputted into an assembly file for the whole gearbox to be assembled





## Decide


## Appendix
Selected Bearings Used: Bronze Sleeve Bearing 6391K126 and 6391K611

