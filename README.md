# graph_editor
A 3D editor for directional graphs


There are two movement modes that can be switched by pressing M key:
* In the first mode, the camera moves paralled to an axis. Keys W and E control movement along x-axis, keys S and D control movement along y-axis and keys X and C control movement along z-axis.
* In the second mode, pressing W would move the camera forward, pressing S would move the camera backward and pressing A and D would move the camera to the right and to the left respectively.


In both modes, the camera can be rotated using arrow keys.


Pressing G would create a 3x3x3 grid of spheres around current position of the camera. After moving the camera out of the grid, the user can click one or more spheres to turn them into graph vertices. Pressing H would remove all grids but leave the spheres that were clicked intact.
