## Overview
This project implements an interactive sphere using WebGL. A sphere is a symmetrical three-dimensional object defined as the set of all points in space at a fixed distance (the radius) from its center. In computer graphics, spheres are widely used as basic examples of curved surfaces due to their smoothness and ease of shading calculations.

In this project, the interactive sphere is created by recursively subdividing a starting geometry and using shading techniques to simulate light interaction with the surface. This approach is designed to showcase fundamental WebGL programming methods and introduce interactive elements for user engagement.
## Features
Recursive Sphere Generation: The sphere's geometry is based on recursive subdivision of an initial polyhedron to approximate a smooth surface.
Shading Computations: Basic lighting and shading techniques are implemented to simulate the effect of light on the sphere’s surface.
User Interaction: Users can interact with the sphere by rotating it or adjusting the subdivision level via keyboard inputs or buttons.
Real-Time Rendering: Dynamic rendering of the sphere based on user inputs and changes in camera perspective.
## Key Components
## WebGL Setup:

WebGL context initialization
Buffer setup for storing vertex positions
Compilation and linking of vertex and fragment shaders
Geometry Generation:

The initial polyhedron (e.g., tetrahedron) is subdivided recursively to generate a sphere-like mesh.
Each recursive step increases the number of triangles, refining the sphere's shape.
Shading and Lighting:

Basic lighting model simulates how light interacts with the surface of the sphere.
Shading calculations are based on material properties, light source position, and surface normals.
User Interaction:

Keyboard and button controls allow the user to rotate the sphere or change the subdivision level.
Interactive transformations are applied using rotation and projection matrices.
