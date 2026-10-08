## Contents 
Grasshopper file and final report for the LVA "`210.011` Parametric Tools for Structural BIM Design" at TU Wien. The task objective was to 
create an optimized truss roof-structure for a squared 10x10m area. Tools: Rhino, Grasshopper, Karamba3D, and Octopus. 


## Criterias and Objectives
Overall the entire structure ought to appear lightweight.
This is achieved by using smaller cross sections for the beams
and empty space between beams/hinges.
These goals compete with structural goals, e.g. minimal
deflection and reduced buckling. The following objectives
capture these considerations:
 - Min. total mass
 - Max. ratio of highest to lowest truss height
 - Min. deflection of beams

### Parameters:
Variability for the optimization process was given by
parametrizing:
- Number of truss segments along the global X-axis
- Number of truss segments along the global Y-Axis
- Beam cross section
- Height-Ratio
The Cross section could also have been optimized using a
dedicated Karamba component Cross Section Optimizer,
but as part of this project was manually optimized by
providing the cross-section selection as a Gene/Parameter
to Octopus

## Selected variants from the solution space:
<img width="576" height="551" alt="image" src="https://github.com/user-attachments/assets/28fb0c60-408f-4844-901e-73161f6f53e4" />
