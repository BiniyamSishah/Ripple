# Ripple
consists mesh files for a simulation over ripples. The simulation is to publish a paper.
description of documents int folders:
04/17/2020 problem I have are two:
1) I can't establish empty front and back faces. It seems I have a 3D mesh and I am trying to take is as 2D mesh.
solution: 1) extrudeMesh untility after importing the mesh from Ansys
               - This is giving me problem.
          2) Construct a 2D mesh in Ansys and use extrudeMesh utility in OpenFoam
               -  Not done yet
          2) Constract a 2d Mesh and extude on Ansys Mesher
               -  Not done yet
               
               The workflow I should be following when constructing the Mesh in Ansys:
               1) prepare half of the ripple geomtry first 
               2) make a symmetric coping about the crest
               3) create a mesh on the face described by (2) : Make sure left and right face are cyclic and the bottom inflation
               4) Extrude mesh and assign face groups
               5) import to openFoam in ascii .msh format
               6) use CreatePatch -overwrite to empty front and back faces.
               
               
          
