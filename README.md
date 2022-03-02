# VoronoiTessellation
Voronoi tessellation with MATLAB and ParaView for visualization in the 3D case.
### 2D Tessellation
For the 2D case the code can divide a square area into N amounts of different zones by setting N different centres placed randomly in the square. The code has different ways of adding borders between zones, the only one that creates same width borders does it by removing any points of the zones that are at the edges of it. The some code that can make the borders can be used to round the tips of the areas (more or less simulating how grains look in a material).

The initial tessellation:

![image](https://user-images.githubusercontent.com/26636053/156362857-9758e2db-86be-4af0-bace-15d060a76ba7.png)

Tessellation after adding borders and rounding the corners:

![image](https://user-images.githubusercontent.com/26636053/156363124-7ff4f2b9-d275-4d28-a6f5-4790d8e8821a.png)

### 3D Tessellation
The code for tesssellation in 3D is almost the same as in 2D but just adding an extra spatial dimension. The code cannot round the corners of the grains for now, it can just add borders to them.
