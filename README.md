# 3D-openGL-project

Title: Making view in the moving car on visual studio
Title of 3D Modelling project should contain techniques and algorithms covered in the lecture and lab session. So, the view in the moving car is picked my assignment project.

![image](https://github.com/MIJI-H/3D-openGL-project/assets/71619429/c7d4244c-c60a-4406-9ca5-c8938cec30c3)

[↑Screenshot of project]

[Road]
The road where the car runs
- Base: Through the solid cube and wire cube, base of the road was created.
- Line: Using the “For” loop, the central line appeared on the road.

[Tree]
As I drove, I expressed the trees that could be seen on the surrounding roads.
It’s combination of Icosahedron and solidcube.
By using fltTreeOffset , I control increment and decrement acceleration


[streetlight]
It showed streetlights around the road.
A “for” statement was used to indicate streetlights arranged at regular intervals.

[Building]
It embodies the surrounding buildings that can be seen when running on the road.
Using glutWireCube, outline of the cube was drawn.
Using glutSolidCude, cube was drawn

Translate was given to trees and building street trees to give the effect of the car moving forward. 

![image](https://github.com/MIJI-H/3D-openGL-project/assets/71619429/67eb467c-78b6-42ca-9e37-cd27bdefe764)
![image](https://github.com/MIJI-H/3D-openGL-project/assets/71619429/9dc599e6-db0e-4919-8815-dd21a6702f80)

[↑ Screenshots of project when using up and down]
(Keyboard interaction) 
U and u make camera up
D and d make camera down 
_ and - make decrease the speed of car movement.
+ and = make increase the speed of car movement.


By setting the sky-blue dark, it indicates that it is night.
![image](https://github.com/MIJI-H/3D-openGL-project/assets/71619429/f7a1fbf3-74a0-43c2-a76c-ff1e49d1d1d3)
[↑ Screenshots of project when write moon code]
I wrote a code to use lighting and to draw the moon in the evening, but the entire window was printed dark because of the shadow part. To solve this part, I googled and tried several times, but failed, posted a screenshot and commented out the code for that part.

