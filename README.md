# 3D-openGL-project <br/>

Title: Making view in the moving car on visual studio <br/>

Title of 3D Modelling project should contain techniques and algorithms covered in the lecture and lab session. So, the view in the moving car is picked my assignment project.<br/>

![image](https://github.com/MIJI-H/3D-openGL-project/assets/71619429/c7d4244c-c60a-4406-9ca5-c8938cec30c3)

[↑Screenshot of project]<br/>

[Road]<br/>

The road where the car runs<br/>

- Base: Through the solid cube and wire cube, base of the road was created.<br/>
  
- Line: Using the “For” loop, the central line appeared on the road.<br/>

[Tree]<br/>

As I drove, I expressed the trees that could be seen on the surrounding roads.<br/>

It’s combination of Icosahedron and solidcube.<br/>
By using fltTreeOffset , I control increment and decrement acceleration<br/>


[streetlight]<br/>

It showed streetlights around the road.<br/>

A “for” statement was used to indicate streetlights arranged at regular intervals.<br/>

[Building]<br/>

It embodies the surrounding buildings that can be seen when running on the road.<br/>

Using glutWireCube, outline of the cube was drawn.<br/>

Using glutSolidCude, cube was drawn<br/>

Translate was given to trees and building street trees to give the effect of the car moving forward. <br/>

![image](https://github.com/MIJI-H/3D-openGL-project/assets/71619429/67eb467c-78b6-42ca-9e37-cd27bdefe764)
![image](https://github.com/MIJI-H/3D-openGL-project/assets/71619429/9dc599e6-db0e-4919-8815-dd21a6702f80)

[↑ Screenshots of project when using up and down]<br/>

(Keyboard interaction) <br/>

 U and u make camera up<br/>

 D and d make camera down <br/>

 _ and - make decrease the speed of car movement.<br/>

 + and = make increase the speed of car movement.<br/>


By setting the sky-blue dark, it indicates that it is night.<br/>

![image](https://github.com/MIJI-H/3D-openGL-project/assets/71619429/f7a1fbf3-74a0-43c2-a76c-ff1e49d1d1d3)
[↑ Screenshots of project when write moon code]

I wrote a code to use lighting and to draw the moon in the evening, but the entire window was printed dark because of the shadow part. To solve this part, I googled and tried several times, but failed, posted a screenshot and commented out the code for that part.

