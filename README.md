# 3D-point-cloud-Visualization
*THIS PAGE IS OPTIMIZED ONLY FOR VIEWING ON PC*

3D point cloud visualization to understand the dense and sparse regions in the data.

This is a computational fluid flow simulation dataset from the San Diego Supercomputing Center. 
You can learn more about the science behind the simulation here: http://www.uni-kl.de/sciviscontest/

Only the data set "058.csv" is used to represent the data from the 120 plus csv files in the data folder. You can change the csv 
points file being read on line number 20 in src/js/main.js.

There are two planes shown in the 3D view. One is the horizontal and the other is the vertical which appears on 
selecting the radio buttons below the 3D view.

When the horizontal plane is checked, the plane can be moved through the points using the "W" and "S" keys on the keyboard.
When the vertical plane is checked, the plane can be moved through the points using the "A" and "D" keys on the keyboard.

The button "X" is used to find the intersection points of the currently active plane and plot the points on the 2D plane beside the 3D view.

The button "Z" is used to replot all the points on the 3D view.</p>
