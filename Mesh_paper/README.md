In all meshes, no. of vertical cells is 150
               no. of horizontal cells is 100
               aspect ration/bias is 20
               allowable max. cell size is 0.005 m
               height of bottom-most cell is 0.00025 m

This are very good meshs. All quality checks had been made and the case files on openFoam have been created. Since in a previous grid independence test, the mesh property outlined above is shown to work well for the smallest and largesrt amplituide of freestream displacments, thier is no need to perform any mesh quality tests.  

It would be a good stratey to check suffcients points are present in the viscous sublayer layer for resolving the flow. 

There were some quality issues with cyclic patch generation in cases, Ap25dp2T7, Ap3dp2T7,Ap8dp2T7 and Ap9dp2T7. The tolerance has to be  reduced to have the quality check of openFoam give a green flag. The errors are most probably related to disimilarites between left and right cells generation durin meshing. A tolerance of 0.001 was used for all other meshs not mentioned here, 0.01 and 0.01 were used for the first two and last two meshes, respectively. 
