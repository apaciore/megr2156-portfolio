# A8 – Gears

## Objective
The objective of this assignment is to design a gearbox that can be assembled and disassembled. The input and output shafts are to be sized and the strength to be calculated for. The gearbox housing must have proper clearance and fastening. We need to model and design this gearbox parametrically in CAD, and make engineering drawings for all the parts used.


## Hand Calculations and Design Specs

![handcalc1](Screenshot%202026-11-02%20133008.png)
![handcalc2](Screenshot%202026-11-02%20133039.png)
![handcalc3](Screenshot%202026-11-02%20133100.png)
![handcalc4](Screenshot%202026-11-02%20133116.png)


I chose to opt for a simple design, where the two halves of the gearbox snap fit to enclose the gears. Because the gears have a diameter of 0.402 in and 1.027 in each. To allow adequate clearance and space for the user to slide the gears into the box, I decided to make the box 2.5 in width and 2 in length. The size of the journal bearings require the walls to be 0.25 in thick so that way the shaft is able to stick out of the gearbox adequately. To ensure that the gears can spin freely, a total depth of 1 in made sense- total being the depth with the face snapped on. 

![handdrawing](Screenshot%202026-11-02%20132932.png)

## CAD Modeling

![mothertable](Screenshot%202026-11-02%20132014.png)

I sketched my box to my decided length and width, and extruded it to a depth of 0.9 in, leaving 0.1 in for the width of my other half of the gearbox.

![cad1](Screenshot%202026-11-02%20133605.png)

I sketched another rectangle onto the face of this prism, 0.25 in inward from all sides, and then cut extruded the shape to 0.25 in away from the back of the box. This create a shell with a thickness of .25 on all sides except the front face, which is left completely open to insert the gears.

![cad2](Screenshot%202026-11-02%20134725.png)

I sketched the four pin holes at the center of the four corners of the shell on the side with the open face. The holes were sketched to a diameter of 1/8 in as that would be the size of snap fitting pins used, and I cut extruded these circles to a depth of 0.25 in. 

![cad3](Screenshot%202026-11-02%20145215.png)

I sketched circles with diameters of the input and output shaft on the back face, and cut extruded all the way through to create the holes for the input and output shafts.

![cad4](Screenshot%202026-11-02%20150918.png)

I then moved onto the other side of the gearbox assembly. I sketched the length and width the same as the previous part, and extruded it to the remaining 0.1 in. I then drew the 4 pin circles in the same position as previous, but extruded them to a length of 0.25 in rather than cut extruding and making holes. This was all the steps for the second half of the gearbox.

![cad5](Screenshot%202026-11-02%20152452.png)

I then modeled the two different shafts in CAD, one at 0.125 in diameter and the other at 0.25 in diameter, and both 1 in in length.

![assembly1](Screenshot%202026-11-02%20155844.png)

All of the parts were then inputted into an assembly file for the whole gearbox to be assembled.

![assembly2](Screenshot%202026-11-02%20162535.png)

## Engineering Drawings of Designed Parts

![draw1](Screenshot%202026-11-02%20163005.png)
![draw2](Screenshot%202026-11-02%20163159.png)
![draw3](Screenshot%202026-11-02%20164029.png)
![draw4](Screenshot%202026-11-02%20164002.png)

## Appendix

Selected Bearings Used: Bronze Sleeve Bearing 6391K126 and 6391K611

[Download CAD Assembly](gearboxassembly.SLDASM)


