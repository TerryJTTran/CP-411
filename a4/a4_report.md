# A4 Report

Author: Terry Tran (sign your name here)

Date: 2021/11/09   (insert the date)

Check [readme.txt](readme.txt) for lab work statement and self-evaluation. 

## Q1 Culling, Lighting, Shading (short_answer)
	
### Q1.1 Concepts of culling

- The difference between culling and clipping is that in culling the objects not in the frame of the camera are removed, leaving fewer polygons to process. While in clipping the polygons that are beyond the camera are removed.
- The difference between object precision and image precision hidden surface removal algorithms is object precision algorithms will generate all objects in order of furthest from the camera view. While image precision will generate all objects simultaneously and determine the visiblity from the edges and vertices at each pixel position on the projection plane. Examples of both respectively are BSP-Trees and scan line algorthim.

### Q1.2 Culling computing

![Back face and depth calculations.](images/a4q1.2.jpg){width=90%}

### Q1.3 Concepts of lighting and shading

- The four light models are directional, point, ambient, and emission.
- A light model determines the light intensity of a surface based on the light source, object, and reflect light.
- A shading model determines how a pixel color is calculated based on the light reflections, the models are constant, gouraud, and phong shading.
- The Gouraud shading model interpolates the colors of vertices.

### Q1.4 Lighting computing

![Reflection intensity calculations.](images/a4q1.4.jpg){width=90%}

## Q2 OpenGL culling, lighting, shading (lab practice)
	
### Q2.1 Hidden surface removal
 
Complete? (Yes/No) 

If Yes, insert a screen shot image to show the completion.

![Simple culling](images/2.1.1.png){width=90%}
![Pass and render cube data](images/2.1.2.png){width=90%}

If No,  Add a short description to describe the issues encountered.

### Q2.2 Lighting and Shading
 
Complete? (Yes/No) 

If Yes, insert a screen shot image to show the completion.

![Drawing a Lit Sphere](images/2.2.1.png){width=90%}
![Moving a Light with Modeling Transformations](images/2.2.2.png){width=90%}
![Programming material properties](images/2.2.3.png){width=90%}
![General lighting and shading](images/2.2.4.png){width=90%}

If No,  Add a short description to describe the issues encountered.



## Q3 SimpleView2 - culling, lighting, shading (programming)
	
### Q3.1 Culling
 

Complete? (Yes/No) 

If Yes, insert a screen shot image to show the completion.

![Hidden surface removal](images/3.1.png){width=90%}

If No, add a short description to describe the issues encountered.



### Q3.2 Lighting
 

Complete? (Yes/No) 

If Yes, insert a screen shot image to show the completion.

![Light models](images/3.2.png){width=90%}

If No, add a short description to describe the issues encountered.



### Q3.3 Shading
 

Complete? (Yes/No) 

If Yes, insert a screen shot image to show the completion.

![Shading models](images/3.3.png){width=90%}

If No, add a short description to describe the issues encountered.



### Q3.4 Animations
 

Complete? (Yes/No) 

If Yes, insert a screen shot image to show the completion.

![Multiple animations](images/3.4.png){width=90%}

If No, add a short description to describe the issues encountered.






**References**

1. CP411 a4
2. Add your references if you used. 
