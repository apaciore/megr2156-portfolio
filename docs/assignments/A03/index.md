# A3 – [Topic]

## Objective

The objective was to design a beam with a circular cross section, given a specific material, with an axial force on one end and a fixed support on the other end, and a maximum deflection. We were tasked with determining the minimum geometry requirements like length, diameter, and weight in order to meet the specifications when under the axial load. We then were expected to verify the the geometry through finite element analysis on CAD, and analyze what the FEA presented and what the formula based hand calculations presented. It was also expected that we documented our design process steps in the CAD application. 

## Analyze
## Parametric Design

![A3calc](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A03/Screenshot%202026-09-09%20211416.png)

I decided on a standard 1 inch diameter for the circular aluminum bar, creating an area of 0.79 in^2. After having to go through several designs after adjusting the material and trying to get closer to the target max deflection as it was reading too high, I decided that I would certainly be using the smallest possible force applied to the beam, 300 lb. After making several adjustments to the aluminum type to try to minimize deflection, I selected 4032-T6 aluminum alloy, and chose my Young's modulus for my beam to be 11.45*10^6 psi. These specifications determined my length of my beam to be 269.78 in. 
There was a strong discrepancy between the hand calculations and FEA. To be completely honest, I was unable to locate the error for the almost exact once decimal place discrepancy, totaling to 905.56% discrepancy. I checked my mother table to ensure that it matched all of the design specifications, and made sure that my selected material had a Young's modulus close to the modulus that was very similar to the one I selected to match the length that I calculated for. After checking all of the factors I could think of, I was left unable to locate the source of the discrepancy, as it appears my setup was consistent and accurate. The only thing plausible would be a one decimal place error somewhere in my calculations, but I simply couldn't locate where. 



![cad1](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A03/Screenshot%202026-09-09%20203639.png)
![cad2](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A03/Screenshot%202026-09-09%20171736.png)
![cad3](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A03/Screenshot%202026-09-09%20203814.png)
![cad4](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A03/Screenshot%202026-09-09%20172044.png)
![cad5](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A03/Screenshot%202026-09-09%20173219.png)
![cad6](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A03/Screenshot%202026-09-09%20170637.png)
![cad7](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A03/Screenshot%202026-09-09%20204129.png)
![cad8](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A03/Screenshot%202026-09-09%20204142.png)

My max stress was much lower than the maximum allowed stress for aluminum according to my hand calculations, as the FEA presented 4.19 * 10^-7 ksi, and the maximum allowed stress is 0.382 ksi. 




![A3calc2](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A03/Screenshot%202026-09-09%20221312.png)

My newly calculated safety factor according to the nominal stress presented by the FEA and the concentration factor for a bar with a pin hole under tension was much higher than the safety factor produced from the hand calculated stress. 

## Decide


## Communicate

Some lessons I learned or mistakes I made is not confirming that there is a material in CAD to conduct the FEA with that has a matching Young's modulus to what I selected and confirmed was consistent with my dimensions in my hand calculations. I wasted quite a bit of time having to redo my hand calculations after attempting to minimize my deflection in the FEA. After completing the assignment, I am still actively looking to understand why the FEA produced a max deflection a whole decimal place higher than expected, when it appears that all of my dimensions and mother table in CAD are consistent with what I hand calculated to produce the correct deflection requirement. I spent around 8 hours completing this assignment. 

