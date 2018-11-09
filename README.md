# geo

Geology experimentations to be introduced in ViaRE.

## Landmass—first methods

Generate a map divided in multiple areas that are either land or water first, 
and modify the heights of each area later.

### Radial wave projection

- Choose a point in the map
- Generate a wave `w`, made from the overlap of multiple waves.
- Sweep around the point using the values from `w` to set a radius.

//**TODO:** Implement something inspired by this idea in any framework//

### Growing trees with particles

- Create a particle at a random point in the map.
- Make the particle move around.
- When a particle is *old enough*, it may reproduce into *n* particles.
- When a particle is *old enough*, it dies, registering its last position.
- Draw a concave hull of the points left by the particles.

//**TODO:** Implement something inspired by this idea in any framework//

### Polygon multi distortion

- Generate an irregular polygon.
- Distort each edge as a vibrating string (like a guitar string being played).
- Fix the points of intersection between the distorted edge before and after
the distortion.
- Distorted edges cannot cross to the other side of the original edge.
- Repeat.

//**TODO:** Implement something inspired by this idea in any framework//

## Heightmaps—first methods

Generate heightmaps and then decide the threshold that divides land from water.