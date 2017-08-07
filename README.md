# Computergrafik-Basecode
This project contains basecode developed for an "Introduction to Computer Graphics" course at the University of Bern. This is educational code intended for students to learn about 3D graphics programming. The framework provides a skeleton for a real-time rendering engine. It is modular to support different rendering back-ends, coming with an OpenGL-based renderer, and a renderer using OpenGL and OpenVR to render onto VR goggles. 

Import this project into Eclipse to work with it. First create an empty folder where your project will be located. Start Eclipse and select the created folder as workspace. Now you can import the Java code to the workspace by selecting the menu entry "File->Import->Git->Projects from Git->Next". Then choose "Clone URI". In the next dialogue "Source Git Repository", use https://github.com/mzwicker/Computergrafik-Basecode.git as URI. Leave the fields "User" and "Password" empty. In the dialogue "Local Destination", choose the created folder. This folder must be empty. After completion of the import you have to wait some seconds for the initialization of the project creation. If the Maven build is not done correctly by default, you have to update the projects by right-clicking on the project name, then "Maven->Update Project...". Afterwards, you should be able to run the project "simple" and see a rotating cube. If you use an older version of Eclipse, you may have to manually install the plugins for "Maven" and "Git" separately. 


Branch to test IPD changes.

1 cm = 0.01 gameunits

Variable ball distance = [25, 45) cm

Factor to vary between 0.7, 1, and 1.3 * IPD

Make sure to calibrate properly when starting SteamVR