# Computer Graphics, Winter Semester 2023

- **Name:** Your name, e.g., Maxi Musterfrau
- **E-Mail:** Your e-mail, e.g., maxi@musterfrau.de
- **Matriculation no.:** Your matriculation number: 123456789

<!--------------------------------------------------------------------------->
## Assignment 1

### Assigment 1a

* WebGL 2:

- Vertex Shader (VS):
The vertex shader is a program that processes each vertex of a 3D model before it is transformed into screen coordinates.
It is responsible for tasks such as transforming the vertex positions, applying lighting calculations, and passing data to the next stages of the pipeline.
The input to the vertex shader is typically vertex attributes, like position, color, normals, etc., and it can output transformed vertex positions and other interpolated values.

- Fragment Shader (FS):
The fragment shader, also known as the pixel shader, operates on each fragment produced by rasterizing the primitives (points, lines, or triangles) in the scene.
It is responsible for tasks like determining the final color of a pixel, applying textures, and handling lighting calculations.
The input to the fragment shader includes interpolated values from the vertex shader, such as colors, normals, and texture coordinates.
The fragment shader outputs the final color for each pixel.
-----------------------------
1- Determine the light position inside vertex sheder "lightPosition".
2- Calculate the outcolor in fragment shader depends on ambient,diffuseColor,specularColor and shininess. 

### Assigment 1b
- I add X, Y , and Z controler parameters to the material page with the ambient, diffuse, and specular contributions parameters contollers.
- use those variables in the section vs and fs to update the light position and other parameters.

### Assigment 1 Extras
<!-- Describe any extra features that you implemented. Make sure to cite your sources. -->

<!--------------------------------------------------------------------------->
## Assignment 2

### Assignment 2a
- The ambientMap, diffuseMap, and specularMap parameters aare already exist in the matireal page.
- after the user insert the map we can use it to do texturing.
- we will add the parameter a_texcoord to vs section.
- then update the finalColor in fs section and use texturing function.


### Assignment 2b
<!-- Briefly describe your solution. If you did not solve the assignment, simply enter "Not solved." -->

### Assignment 2c
<!-- Briefly describe your solution. If you did not solve the assignment, simply enter "Not solved." -->

### Assigment 2 Extras
<!-- Describe any extra features that you implemented. Make sure to cite your sources. -->

<!--------------------------------------------------------------------------->
## Assignment 3

### Assignment 3a
<!-- Briefly describe your solution. If you did not solve the assignment, simply enter "Not solved." -->

### Assignment 3b
<!-- Briefly describe your solution. If you did not solve the assignment, simply enter "Not solved." -->

### Assignment 3 Extras
<!-- Describe any extra features that you implemented. Make sure to cite your sources. -->

<!--------------------------------------------------------------------------->
## Assignment 4

### Assignment 4a
<!-- Briefly describe your solution. If you did not solve the assignment, simply enter "Not solved." -->

### Assignment 4b
<!-- Briefly describe your solution. If you did not solve the assignment, simply enter "Not solved." -->

### Assignment 4 Extras
<!-- Describe any extra features that you implemented. Make sure to cite your sources. -->