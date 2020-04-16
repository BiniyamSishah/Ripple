ripple1.msh: inverted(cyclic in z direction) mesh with global cell size =0.005 and simplegrading 30, bottom cell=0.0001, 100 vertical lines.Only a tolerance of 10 worked below thast createPatch gives bad mesh. 


ripple2.msh: like ripple1.msh but cyclic in x direction. tolerance of 10 doesn't work.
ripple3.msh : like ripple2.msh but a reduced resolution mesh. done to test openFOAM. 
ripple4.msh : is like ripple3.msh except that mesh maching was performed. 
rippel5.msh : is simila to rippel4.msh except that the bottom cell has been refined. 
