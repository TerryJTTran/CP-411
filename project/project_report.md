# Project Report

Title: Galactic Visitors

Author(s): Terry Tran

Date: 2021-12-07

Check [readme.txt](readme.txt) for  project statement and self-evaluation. 

## R1 Proposal (proposal)
	
### R1.1 Application and problem description
 
Add a link to the project proposal. 

[project proposal](proposal.html)


Write a comment if your project implementation is different what you proposed.
Project no longer includes a 3D aspect and is not a perfect replication of space invaders. The name was also changed to Galactic Visitors. 

## R2 Design & implementation (programming)
	
### R2.1 Problem solving and algorithms
 
Write a paragraph to high light how you solved the problem in your project. 

You can use screen shot to show the result of your solution. 

There were issues when developing shot collision, alien animation and assigning different colors to different objects. 
When making shot collision there was an issue differentiating between each object but the solution was to designate specific ids to objects so they could be found by simply searching for the id.
The issue with the alien animation was that the furthest left and right alien must reach the end to change direction, but when aliens are destroyed it becomes difficult to locate the most right or left alien.
The solution I found was to designate the start most left and right aliens in the top row at the start, then when those aliens are eliminated check all the ids for next alive alien that is the most left or right.
This solution was chosen because the top row should be the last row to eliminate and to ensure that in the case that it is eliminated before last that the correct alien if selected.
The issue of assigning different objects different colors occurred because each object was formed from cube objects, making the general color values of the cube static for all objects.
The solution to this was to create a method in the cube class that would take rgb float values and set the cube object equal to them, thus after each object is create I simply call the method.
The issue about potential performance issues due to the many objects appeared to not be an issue.
One issue that I was unable to solve was that opensound does not support multiple sounds playing simultaneously, thus when the game is played some sounds are cutoff.

### R2.2 Completion of the project
 

Give a list of completed features of your project.

You can use screen shot to show the result of the features. 

![Features](images\features.png){width=90%}

Completed features include:

- Tank movement.
- Tank firing.
- Bullet movement.
- Bullet/Alien explosion.
- Different colored objects.
- Alien movement.
- Alien progressive speed increase.
- Sound effects.
- Key inputs.

### R2.3 New features
 
Give a list of new features on CG objects and OpenGL you used in the project. 

You can use screen shot to show the result of the new features. 

![Objects](images\organization.png){width=90%}

- Tank object.
- Bullet object.
- Alien object.
- Explosion object.
- Animation control.
- Sound effects. 

### R2.4 Program design and organization
 
 
Write a paragraph to explain your program design and organization. 
 
You can use screen shot to show the program structure. 

The program was designed using the SimpleView3 assignment developed in class.
The new objects required for the project were created by developing their own classes.
The animation methods were stored in the animation class as a central file that could use all the other files without conflict.

## R3 Project presentation (document)
	
### R3.1 Project documentation
 
This report is used as document. Alternatively, you can write a separate document in text, md, or html format, and add the link to the file.  

[Project document](document.html)

### R3.2 Project demonstration
 
Add the link to the media file of your project demonstration. **You don't need to include the demonstration video if you demonstrated your project in class**. 

[Project demonstration](images/video file name)

**End**