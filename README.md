# BCC-4
4-valued coordinate system for the Body Centered Cubic (BCC) grid and applications programs

SUMMARY

Software here is associated with paper:

Title: Repairing 3D Binary Images Using the BCC Grid
with a 4-valued combinatorial coordinate system

Authors: Lidjia Comic (University of Novi Sad, Serbia), 
         Paola Magillo (University of Genova, Italy)

Published in Elsevier Journal "Information Sciences",
special issue on Digital Manifolds.
Accepted for publication in February 2018.

This software implements the coordinate system for the BCC grid,
the program for transforming a given cubic image into a 
well-composed BCC image, 
and programs to compute the boundary surface and the Euler
characteristics of the well-composed BCC image.

We include the program to generate random input cubic grids of
given sizes, and programs to convert both cubic and BCC images 
into a suitable format for visualization.

LIST OF ITEMS

Data
    Implementation of BCC coordinate system.

Repair
   Program to repair a given cubic image into a 
   well-composed BCC image.

GeneraVTK
   Programs to generate a VTK format from cubic and BCC grids.
   The VTK format is accepted by paraview visualization program.

Cubes
   Program to generate random cubic images.

Algo/Boundary
    Programs to reconstruct the boundary surface of a BCC image 
    and to compute the Euler formula.

Each folder has a file called index.html which can be loaded into
the browser and contains the documentation.

Each folder has a makefile. Just cd to the folder and type 'make'
to compile and generate the executable files.
