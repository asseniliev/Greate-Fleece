# The Great Fleece
The Great Fleece is created following the course ["The Ultiamate Guide to Cinematography with Unity"](https://risesmart.udemy.com/course/the-ultimate-guide-to-game-development-with-unity/learn/lecture/34331704#overview) by Jonathan Weinberger.
It introduces cutscene development uning timeline and cinemachine and teaches more intermediate C# game programming concepts. It also explores lighting and post-processing effects and uses [The Great Fleece] asset pack created specially for the course.
The course itself is constructed on learn by doing principle; each game feature is introduced as a challenge and while the game design and the assets used are fully copied from  the course, the huge part of the C# implementation is my own work and in many places diviates significantly from the code provided by the course solution. 

## Project progress
21-Jan-2023: 
  - Project created; asset [The Greate Fleece](https://assetstore.unity.com/packages/templates/tutorials/the-great-fleece-110186) imported from the Asset Store
  - Ended up with video 181 - Albedo channel: practice working with Standard shader, attach texture to an object, manipulating with 'Metalic' and 'Smoothness' properties
22-Jan-2023:
  - Meshes and sub-meshes; using array of materials in 'Mesh Renderer' component
  - Creation of new materials and assignment of materials to meshes. Transparent glass material with standard shader / Transparent rendering mode.
  !['Basic materials Practice'](/Pics/Basic%20Material%20Practice%201.JPG)   
  - Challenge: make-up the painting wall: task is to put materials on the painting wall and make it look as the provided template. My result (template is at the left, my work is at the ight):
  !['Painting wall challenge'](/Pics/Painting%20wall.JPG)
  - Usage of occlusion maps to create false shadows; ended up with video 186