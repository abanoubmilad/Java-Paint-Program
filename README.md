﻿#Object Oriented Drawing and Painting Application

#####Copyright (c) [2014] [Abanoub Milad Nassief] [abanoubcs@gmail.com]

###Part 1: Geometric Shapes Data Model
Geometric shapes belong to different groups (ex: Elliptical Shapes, Polygons, Sectors, etc). Members of these different groups are related to each other in the sense that they share common properties. The design model takes these relations into consideration In order to be able to implement an efficient and object oriented drawing application. 

###Part 2: Drawing and Painting Application
Drawing and painting applications are very popular and have a huge user base. They generally offer a big number of features that includes but is not limited to: Drawing, Coloring, and Resizing. They also include a number of built in, and possibly extensible set of geometric shapes, and classically, they allow the user to undo or redo any instructions so as to make the application more usable.
A very important feature is editing the painting, either by moving, deleting or resizing any object.
One of the main features in any paint application is saving user’s drawings in a file and modifying it later.
The concept of dynamic class loading is widely spread in computer applications. It is an option that allows the user to extend application features at runtime. This can be easily done by the dynamic class loading capabilities that Java offers.

###what this app offers/does:
1. A GUI that allows the following functionalities for the user on all the shapes defined in part 1:
	* Draw with specific color, and Edit the color of selected objects.
	* It would allow the user to undo or redo any action performed.
	* The cursor should be used to select the location of a shape while drawing it, or moving it to another location, for more accurate control on the shape parameters (ex: size), dialog boxes could be used.
	* Allow the user to select an object by clicking on it, and then start to resize, move or delete.
	* When an object is selected, its appearance changes such that the user understands that it is selected.
	* While resizing, small boxes appear that the user can drag in order to resize the shape.
	* Allow the user to group objects to resize, move or delete together as one object.

2. Provide an option in the GUI of that allows for selecting the class library file(new shape different of the Shape Classes listed in part 1 are previously compiled as a class library). On selecting and loading the file, the isolated shape is appended to the available list of shapes in the application.
3. Provide an option in GUI to save the drawing in XML or JSON file.
4. Provide an option to load previously saved drawings and modify the shapes.
5. User can choose where to save the file.

##Sample Runs

![](sample_runs/ss1.jpg?raw=true)
![](sample_runs/ss2.jpg?raw=true)
![](sample_runs/ss3.jpg?raw=true)
![](sample_runs/ss4.jpg?raw=true)
![](sample_runs/ss5.jpg?raw=true)
![](sample_runs/ss6.jpg?raw=true)
![](sample_runs/ss7.jpg?raw=true)
![](sample_runs/ss8.jpg?raw=true)
![](sample_runs/ss9.jpg?raw=true)
