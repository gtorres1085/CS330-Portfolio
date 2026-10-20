# CS 330 Computational Graphics and Visualization

This repository contains my final project for CS 330. For the project, I created a 3D home workspace using C++ and OpenGL. The scene includes a laptop, coffee mug, desk lamp, smartphone, and a textured wooden desk. I also added lighting, materials, camera controls, textures, and perspective and orthographic views.

## How do I approach designing software?

This project helped me get better at breaking a larger idea into smaller pieces. Instead of trying to build the entire scene at once, I started with basic shapes and gradually combined them into more detailed objects. For example, the laptop was built from boxes and cylinders, while the mug used a cylinder and torus.

My design process was very iterative. I would build something, run the program, look at how it appeared, and then make adjustments. I did this several times with the laptop frame, hinges, mug handle, lamp, and phone. This taught me that designing software is not always about getting everything right the first time. Testing and improving small parts as I go is a strategy I can use in future projects.

## How do I approach developing programs?

One of the biggest development strategies I used was working in small steps and testing after each change. This was especially useful because graphics programming can fail visually even when the code compiles correctly. I learned to test transformations, textures, lighting, and camera movement separately before combining everything.

Iteration played a major role throughout the milestones. The project started as a few basic 3D shapes and eventually included textures, camera navigation, lighting, materials, and multiple objects. I also learned how important file organization is after dealing with texture and shader paths that worked on my computer but had to be changed so the project could run on another system.

My approach to coding has become more organized because I now understand the value of reusable functions and keeping different responsibilities separate. Functions such as `LoadSceneTextures()`, `DefineObjectMaterials()`, `SetupSceneLights()`, and `SetTransformations()` made the project easier to manage and troubleshoot.

## How can computer science help me in reaching my goals?

This course gave me more experience with C++, debugging, libraries, coordinate systems, and working with larger programs. Even though I do not plan to specialize in computer graphics, the problem-solving skills I practiced can be applied to many areas of computer science.

Computational graphics also gave me a better understanding of how software can create interactive visual environments. In future courses, I can use what I learned about programming, debugging, modular design, and user interaction. Professionally, these skills can also help me as a software developer because they strengthened my ability to break problems into smaller parts, test solutions, and improve a program through iteration.
