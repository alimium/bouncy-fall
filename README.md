# Bouncy Fall: A physics simulation
This project aims to simulate a spherical object (a ball) that is thrown at an arbitrary initial position and velocity into a fluid.

The complete documentation and visualizations can be found within the notebook itself. The following is the list of tunable parameters.

> Note that air and fluid drag is considered to be linearly proportional to the velocity for simplicity.

| Parameter | Description |
| --------- | ----------- |
| `c_air`   | Drag coefficient for air |
| `c_fluid` | Drag coefficient for fluid |
| `rho_fluid` | Density of the fluid |
| `g` | Gravitational constant |
| `m` | The mass of the object |
| `r` | The radius of the object |
| `alpha` | The smoothness factor for the switch function |

## Future work!
1. One way to make the simulation more realistic is to calculate the dynamic drag force of the object in the air or the fluid.
1. Also, taking the surface tension into account will dramatically improve the simulation quality. Currently the ball just jumps out of the fluid due to the bouyant force.

## Resources
Here are the resources that I used in this project.

[1] Boyce, W. E., DiPrima, R. C., Meade, D. B. (2017). Elementary Differential Equations. United Kingdom: Wiley.

[2] [Reynolds Number @ Wikipedia](https://en.wikipedia.org/wiki/Reynolds_number)

[3] [Drag (physics) @ Wikipedia.org](https://en.wikipedia.org/wiki/Drag_(physics))

[4] [Drag Forces in Fluids by  
Peter Dourmashkin @ LibreTexts Physics](https://phys.libretexts.org/Bookshelves/Classical_Mechanics/Classical_Mechanics_(Dourmashkin)/08%3A_Applications_of_Newtons_Second_Law/8.06%3A_Drag_Forces_in_Fluids)

[5] [Surface Tension by Benny Lautrup @ Georgia Tech](https://cns.gatech.edu/~predrag/GTcourses/PHYS-4421-04/lautrup/7.7/surface.pdf)



