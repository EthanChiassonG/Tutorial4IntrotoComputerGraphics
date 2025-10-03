This is a submission for the tutorial assignment #4 in the Intro to computer graphics course. inside is a simple scene displaying 3 models with 3 different kinds of lighting applied. there is a seperate folder titled Shaders and Materials in the assets folder that holds the graphs that made the shaders.

Lamberts lighting is calculated by finding the dot product of the light direction and a surface normal, ambient lighting is taken from our environmental lighting and added onto the base lambert model, Specular lighting takes the refleced direction of the light, and compares it with the view direction of the camera and when they overlap is when you can see the light. It's added overtop the other 2 lighting effects.

Leftmost  is Lambert + Ambient + Specular
Middle is Basic Lambter with Ambient lighting 
Rightmost  is just a basic diffuse/Lambert lighting 

<img width="624" height="291" alt="image" src="https://github.com/user-attachments/assets/0f95cbc8-166f-4546-b59f-d5bf5b0feeb7" />
