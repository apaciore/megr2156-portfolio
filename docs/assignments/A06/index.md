# A6 – [Topic]

## Objective

The objective of this assignment is to utilize the bracket design we modeled in the last assignment to make a CAD model of it, and then and engineering multiview drawing from that, including dimensions and tolerances. A goal is to design it in CAD in a way that accommodates factors of both the strength and stiffness analysis of the previous assignment's design.

## Part Modeling Process

The first thing I executed in CAD was the extrusion of Feature A at 1.5 in and a diameter of 0.523 in, in order to accommodate by the strength analysis.
![cad1](Screenshot%202026-09-27%20170315.png)

After I made that extrusion, I sketched Feature B's cross section on the end of it and extruded it to a thickness of 0.1669 in per my stiffness analysis requirement. 
![cad2](Screenshot%202026-09-27%20174715.png)

I then sketched Feature C to a total width of 2.5 in, and a length of 1.5 in to be flush with the length of Feature A, and extruded the sketch to a height of 0.5313 in for the stiffness analysis.
![cad3](Screenshot%202026-09-28%20210315.png)

My next step was to sketch 2 arms at a width of 0.192 in for stress analysis on top of Feature C, and extruded this sketch 1.5 in high. This created my Feature D.
![cad4](Screenshot%202026-09-28%20210945.png)

The last step for creating the CAD model of the bracket was to sketch the flanges on the top of Feature D, and extrude it to a height/thickness of 0.5477 in to accommodate my stress analysis for Feature E. This gave me the complete CAD model of my bracket.
![cad5](Screenshot%202026-09-28%20211811.png)


## Engineering Multiview Drawing

![drawing](Screenshot%202026-09-28%20223240.png)

## Reflections

a.) For the diameter of Feature A, it was very clear to me to choose the dimension presented by the stress analysis. My stiffness analysis presented a minimum diameter of 0.049 in, which was exponentially smaller than the diameter presented by stress analysis- .532 in. Therefore, it was important to select the diameter presented by stress equations, or else the design would have been ultimately insufficient under just the stiffness analysis requirement. 

b.) The majority of my dimensions I just left default at two decimal places as there wasn't a need for close precision at most areas. The area that I did apply the tightest tolerance was to the part of the bracket where the T-beam slides. This is because a sliding fit requires the size of the bracket at that point to be much closer to the size of the component than how much it matters for the other dimensions. 

Most of the lessons I learned from this assignment involved learning the Solidworks Interface. It has been a while since I have generating an engineering multiview drawing of a part in CAD. I am also new to Solidworks in general, so this was my first time ever creating a drawing in Solidworks. It was a task for me to figure out things like how to size the scale of the different views and change the font size of dimensions. These are things that are needed to make the engineering drawing readable, as the first screenshot I took of my drawing did not have easily readable dimensions. I spent a total of roughly 4 hours on this assignment.

[Click here to download my part](sodesignbracket.SLDPRT)
[Click here to download my drawing](bracketdrawing.SLDDRW)
