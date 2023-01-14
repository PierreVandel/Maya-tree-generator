# Maya-tree-generator

Author: Pierre VANDEL
02/11/2022

-> PRESENTATION:

Maya script with an interface allowing to generate randomly stylized trees, random number of branches, random position, shape of the trunk and random branches...
Its use does not require any additional files, plugins or scenes. It only uses native Maya features.

-> INPUTS:

Number tree: Number of trees generated in the scene.
Ramifications: branching level (0: just the trunk, 1: branches are generated on this trunk, 2: branches are generated on these branches, ...)
Snap: Allows you to snap the bottom of each tree to a mesh whose name is entered in the "GroundName" input. If the "Snap to" checkbox is checked and the name (transform name) is not filled in, this feature will not work.
Min: value of the minimum position in Y and Z where the shafts can generate.
Max: value of the maximum position in Y and Z where the shafts can generate.

Generate trees: Starts the generation of trees according to the previous parameters.
Clean trees: Removes all trees from the scene.

-> TO TEST THE SCRIPT:

All default inputs give a first preview.
The values ​​of the inputs are limited so as not to have too long a generation time.
To test the snap, create a plane with a scale of 10, add deformations on the Y axis, check the "snap to" checkbox and enter a name of the transform of the plane in the input ex: "pPlane1"
