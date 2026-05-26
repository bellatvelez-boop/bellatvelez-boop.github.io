


After much thought and consideration, I have decided to pivot toward an interactive triangle visual using OpenGL and PyGame. The model I have thus far is inspired by the triangle section on the online platform, Math is Fun: [Interactive Triangles](https://www.mathsisfun.com/geometry/triangles-interactive.html). The first thing I did was look at a ton of tutorials to get a feel for how PyGame works. Then I imported OpenGL, PyGame, NumPy, and Math. 

Here are the links to all the tutorials I have used thus far:

[Make Games with Python and  PyGame  - PyGame Thursdays 1](https://www.youtube.com/watch?v=wRiCKCdnLHY&list=PLCC34OHNcOtpOG96Uwh3VGkmpZ7qTB5dx&index=1&t=1018s)
[Drawing Shapes In Pygame - Beginner Tutorial](https://www.youtube.com/watch?v=YDP1Hk7uZFA)
[Matplotlib Tutorial 1 - Introduction and Line](https://www.youtube.com/watch?v=q7Bo_J8x_dw)
[Using The Mouse In Pygame - Beginner Tutorial](https://www.youtube.com/watch?v=YbouZ2X8fGk)
[Get Text Input in Python/PyGame in 9 mins!](https://www.youtube.com/watch?v=kDSdjsdoGOY&t=27s)
[OpenGL Tutorial 2 - Triangle](https://www.youtube.com/watch?v=hYZNN0MTLuc&t=5s)
[OpenGL with Python for Beginners: Perspective Projection](https://www.youtube.com/watch?v=LL2V6TM7ABY&t=140s)

Next, I initialized the program window, set up fonts and colors, and defined three coordinate points that act as the vertices of the triangle. I used Pygame’s drawing functions to render the triangle and its sides on the screen.
After building the visual part, I added mathematical functions to calculate geometric values such as side lengths, triangle area, and interior angles. The side lengths are found using vector distance formulas; the area is calculated using the coordinate method; the angles are found using dot products and trigonometry, then converted from radians to degrees. These values are continuously displayed next to the triangle, so students can immediately see how the measurements relate to the shape.
I implemented keyboard controls using the arrow keys, allowing the entire triangle to move around the screen interactively. I also used delta time to keep movement smooth and frame-rate independent. 
As of now, besides moving the triangle itself, the visual is just a visual, and I still need to figure out how to incorporate user input. In an ideal world, I would like the user to be able to drag the triangle's vertices and have the information in the sidebar update in real time. But I might have the user manually enter data into boxes on the screen. 


