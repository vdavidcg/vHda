# vHda
  
This package is a collection of personal Houdini Digital Assets (HDA) and their python module if any  
  
## Overview

### OBJ

* **hudInfo** : Displays context info (scene name, frame range, user name... etc) in specified camera that can be flipbooked and rendered
# TODO : Add camera name
# TODO : Add font parameter
# TODO : Add node info : parm to select a node, groups and parm relative references returned in a dict then shown in text format.geometry
# TODO : find a way for users to choose which parameter they want shown

### SOP

* **arnoldPref** : Creates a Pref attribute for shading work with Arnold
* **colorFromVelocity** : Adds ramp color to points based on a velocity attribute
* **fastMovingPyroSource** : Creates a burn/temperature pyro source from fast moving surface geometry
* **insideUvs** : Deploys uv for fractured geometry inside faces based on a name attribute
* **mayaHoudiniScale** : Scales geometries, VDB grids and particle attributes for import and export from Houdini to other DCCs
* **raise** : Raises pieces with a piece attribute or particles with a pscale attribute to ground level
* **vdbFromAnimatedCam** : Generates a single VDB from the frustrums of camera animated over time

### DOP

* **stopRollingPieces** : Helps with stopping rolling pieces in bullet simulations
