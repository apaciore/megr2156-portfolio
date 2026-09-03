# A2 – Truss Stress Analysis

## Objective
To design a lightweight planar truss using A500 steel, create free body diagrams of crucial pins and joints, find required cross sectional area of truss elements with safety factor, determine pin sizes based on shear forces with a safety factor, estimate the total weight of the truss and pins, create a CAD model of the design with accurate dimensions and weight predictions, compare CAD weight prediction to hand calculations, and document key engineering lessons learned.

![obj](https://private-user-images.githubusercontent.com/319025345/644667079-78e9c3e8-249e-45f5-959b-db6fa12fc66d.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODgzOTUwNDQsIm5iZiI6MTc4ODM5NDc0NCwicGF0aCI6Ii8zMTkwMjUzNDUvNjQ0NjY3MDc5LTc4ZTljM2U4LTI0OWUtNDVmNS05NTliLWRiNmZhMTJmYzY2ZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwOTAzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDkwM1QwMDE5MDRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03MjNmYzJkZmI4MmM0ZDdlMjdjMzk3ZTgwYzUzODQwMzM1MDNiNGZlZGQxZTE5YjgyNDk2NjI1NDJiNmQwZDNiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.hAEcIzcvQVcWuGdhpXCV5EO8D6s8Xk0FRzvvIz2gilE)

The parameters are stated here:
P = 20-30 kN, a = 0.4 m, b = 0.3 m, Point A is a pin and Point B is a roller

## Analyze

## Design of Truss Geometry

![geo](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A02/IMG_4235.heic)

The design I have come up with aims to optimize strength at the expense of a small amount of weight and added material. You can place it in the medium ground on the front of weight, material usage, and strength, perhaps a well rounded design in theory.
 
## Truss Calculations

![calc1](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A02/IMG_4236.HEI)
![calc2](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A02/IMG_4237.HEIC)

The largest internal force that I calculated in the entire truss was 16.02 kN. The minimum cross-sectional area was denoted symbolically using yield strength, safety factor, and largest internal force. After rearranging the equation to solve for the minimum cross-sectional area, I just plugged in all my known variables.
The weight of the truss was calculated first by determining the total length of the A500 steel that was used. After I determined that number, I multiplied by the minimum area to find the volume of the truss. Then, the given steel density was multiplied by that calculated volume to find the total mass of the truss. From there, you just have to multiply that mass by the gravity constant to get the expected weight of the truss.

## Pin Calculations

![calc3](https://github.com/apaciore/megr2156-portfolio/blob/main/docs/assignments/A02/IMG_4238.heic)

The needed values that needed to be calculated were the allowable shear stress, pin cross-sectional area, pin diameter, and pin weight. After identifying my number of pins, and drawing a free body diagram of Pin D, I solved symbolically for the shear stress in the pins. This left me with an equation to find the area of a pin, where I just plugged in my known values. After rearranging the area formula for diameter, I just plugged in my values to find the corresponding diameter. From there, I could find the length of a pin after having the diameter, and plugged that in to find the volume of a pin. The volume could be multiplied by the given steel density to find the weight of one pin. That weight just has to be multiplied by the number of pins I had (7) to get the total weight of the pins. 

## Engineering Lesson
An engineering lesson I learned or was reminded of at least is that the maximum force is the force that is always going to be used when calculating the minimum cross sectional area. This is due to the fact that the components have to be able to deal with the greatest amount of stress that is applied to the bridge, safety factor aside.
