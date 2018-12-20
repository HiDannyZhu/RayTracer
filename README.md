[![Maintenance](https://img.shields.io/badge/Developer-Danny_Zhu-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![Maintenance](https://img.shields.io/badge/Microsoft_Visual_Studios-C++-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
# RayTracer
![.](https://github.com/HiDannyZhu/RayTracer/blob/master/Images/DScene2.png)
# Disclaimer!
  I am unfortunately not able to share this source code due to academic integerity. However, I am able to share the executable and media files, so any interested people are able to run the application themselves. 

The Program was written in C++ utilizing:
- Microsoft Visual Studios C++.
- OpenGL

# Contact for any Questions
- Danny Zhu
  - [Linkedin](https://www.linkedin.com/in/danny-zhu-8b6556119/),
  - chdannyzhu@yahoo.com
  
# Animation made from Images rendered in RayTracer

![.](https://github.com/HiDannyZhu/RayTracer/blob/master/Animation.gif)
  
# Ray Tracing Intro

# Features:

## ViewPlane
![.](https://github.com/HiDannyZhu/RayTracer/blob/master/Images/ViewPlane.png)
To be able to see the images created by the Ray tracer, I had to implement a view plane for our eye camera. Similar to how a camera creates 2D images from pictures on our 3D world, the Viewplane is a graphically way to represent 3D objects as 2D.

## BackWard Raytracing


## Phong Illumination model

No Lights            |  Lighted Sphere                       
:-------------------------:|:-------------------------:|
![](https://github.com/HiDannyZhu/RayTracer/blob/master/Images/MySingleTriangleNoLight.png)  |  ![](https://github.com/HiDannyZhu/RayTracer/blob/master/Images/MySingleSphereLighted.png)|

No Lights With Texture          |  With Texture and Light                      
:-------------------------:|:-------------------------:|
![](https://github.com/HiDannyZhu/RayTracer/blob/master/Images/MytextureTriTest.png)  |  ![](https://github.com/HiDannyZhu/RayTracer/blob/master/Images/MytextureSphereTest.png)|

  
## Reflection
<p align="center">
  <img src="https://github.com/HiDannyZhu/RayTracer/blob/master/Images/MyreflectionTest.png" width="700" height="400" >
</p>

## Refraction
<p align="center">
 <img src="https://github.com/HiDannyZhu/RayTracer/blob/master/Images/MyrefractionTest.png" width="700" height="400" >
</p>

## Reflection & Refraction
Reflection and Refraction       |  Reflective Spheres                 
:-------------------------:|:-------------------------:|
![](https://github.com/HiDannyZhu/RayTracer/blob/master/Images/MyreflectiveSpheres%26Tris.png)  |  ![](https://github.com/HiDannyZhu/RayTracer/blob/master/Images/Myreflection%26refraction.png)|

## Images made by myself
Scene1            |  Scene2
:-------------------------:|:-------------------------:
![](https://github.com/HiDannyZhu/RayTracer/blob/master/Images/DScene1.png)  |  ![](https://github.com/HiDannyZhu/RayTracer/blob/master/Images/DScene2.png)

# How to Run the Program:
  Download the Project_3.rar
  
  KEEP ALL FILE NAMES THE SAME and the same order.
  
  Double-click Project3.exe. 


# How was the Animation made?
After rendering 76 frames by hand, I utilized ffmpeg to create the gif. 

   
# Source for Images/Textures and more info:
https://www.solarsystemscope.com/textures/
Badges:https://github.com/Naereen/badges

# Resources utilized:

Textbook: Peter Shirley, et. Al. Fundamentals of Computer Graphics (4th Edition). A K Peters Ltd; (ISBN:1482229390).

Reference book: OpenGL Programming Guide: The Official Guide to Learning OpenGL, Version 4.5 with SPIR-V (9th Edition). OpenGL Architecture Review Board, Dave Shreiner, Jackie Neider, Mason Woo, Tom Davis. Addison-Wesley; (ISBN1482229390)

