---
title: Master's project
lang: en
content_type: project
---


To obtain my master's degree, I worked on the kinematics of parallel manipulators. Specificaly, I developed a novel method to determine the dexterous workspace of kinematically redundant parallel manipulators. So what is all that? Well, parallel manipulators are unlike most robots we see in the industry. Where industrial robots usually look somewhat like an arm, parallel robots use many arms, called kinematic chains to move an end-effector or tool. To illustrate this, refer to the next figure.

![logo]({{ /assets/images/logo.png | relative_url }})

This figure shows a planar (2D) parallel manipulator of the type on which I worked during this project. We can see three kinematic chains (arms) working together to move a triangular platform. Now, kinematic redundancy can mean a few different things, but in our case it meant adding more joints to each chain, like in the next figure.



In this case, we see that the three chains have an extra joint. 



Finally, what is the dexterous workspace? First, the workspace of a robotic manipulator is the area (planar) or volume (3D) that the tool can reach. The *dexterous* workspace is the area or volume that the tool can reach in *any* orientation. For the manipulators shown in the figures above, this is the area where the tool can reach and rotate 360 degrees.

The old way of determining the dexterous workspace was to sample a large number of points in a large region surounding the manipulator and testing to see if it lies in the space. The sum of all these points is therefore an approximation of the dexterous workspace. The new method, developed in this project, is a little more complicated, but it provides the exact geometric solution. The precision of the new method is therefore dictated by the floating point precision used in the computations and not the number of sampling points.

## Publications
This project resulted in three conference papers as well as three journal papers:

### Journal Papers
-
-
-

### Conference Papers
-
-
- 
