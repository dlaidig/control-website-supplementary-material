# Magnetometer-free Realtime Inertial Motion Tracking by Exploitation of Kinematic Constraints in 2-DoF Joints

Inertial Measurement Units (IMUs) are used to track the motion of kinematic chains in a wide variety of robotic and biomedical applications. However, inertial motion tracking is severely limited by the fact that magnetic fields are inhomogeneous in indoor environments and near electronic devices. Methods that use only accelerations and angular rates for orientation estimation yield no absolute heading information and suffer from heading drift. To overcome this limitation, we propose a novel method that exploits an orientation-based kinematic constraint in joints with two degrees of freedom (DoF), such as cardan joints, saddle joints, the human wrists, elbow or ankles. The method determines the relative heading of the joint segments in real time by minimization of a nonlinear cost function. A filter for singularity treatment ensures accurate tracking during motion phases for which the cost function minimum is ambiguous. We experimentally validate the method in metacarpophalangeal (MCP) joints between the palm and the fingers. Accurate relative orientation tracking is achieved continuously despite several singular motion phases and even though the heading components of the 6D orientations drift by more than 360 degrees within ten minutes. The proposed method overcomes a major limitation of inertial motion tracking and thereby facilitates the use of this technology in robotic and biomechanical applications.

This page provides supporting material for the following publication:

>  D. Laidig, D. Lehmann, and T. Seel. **Magnetometer-free Realtime Inertial Motion Tracking by Exploitation of Kinematic Constraints in 2-DOF Joints**. In *41st IEEE International Engineering in Medicine and Biology Conference (EMBC)*, Berlin, Germany, 2019. https://dx.doi.org/10.1109/EMBC.2019.8857535

This material was previously hosted at https://www.control.tu-berlin.de/2DoF_Joint_Heading_Tracking.

## Video of the performed motions

[![](/files/2dof/2DoF_Joint_Heading_Tracking_Video_Exp1_Preview.jpg)](./files/2dof/2DoF_Joint_Heading_Tracking_Video_Exp1.mp4?raw=true)

Fig. 1: Video of the first experiment. Click on the image to see the video.

[![](/files/2dof/2DoF_Joint_Heading_Tracking_Video_Exp2_Preview.jpg)](./files/2dof/2DoF_Joint_Heading_Tracking_Video_Exp2.mp4?raw=true)

Fig. 2: Video of the second experiment. Click on the image to see the video.

## Detailed result plots

### Index finger, first experiment

[![](/files/2dof/2DoF_Joint_Heading_Tracking_Exp1_F2_Cost.jpg)](./files/2dof/2DoF_Joint_Heading_Tracking_Exp1_F2_Cost.pdf?raw=true)

Fig. 3: Cost function for the index finger during the first experiment.

[![](/files/2dof/2DoF_Joint_Heading_Tracking_Exp1_F2_Delta.jpg)](./files/2dof/2DoF_Joint_Heading_Tracking_Exp1_F2_Delta.pdf?raw=true)

Fig. 4: Top: Estimated and filtered heading difference and interpolated reference value for the index finger during the first experiment. Bottom: Relative orientation error.

### Middle finger, first experiment

[![](/files/2dof/2DoF_Joint_Heading_Tracking_Exp1_F3_Cost.jpg)](./files/2dof/2DoF_Joint_Heading_Tracking_Exp1_F3_Cost.pdf?raw=true)

Fig. 5: Cost function for the middle finger during the first experiment.

[![](/files/2dof/2DoF_Joint_Heading_Tracking_Exp1_F3_Delta.jpg)](./files/2dof/2DoF_Joint_Heading_Tracking_Exp1_F3_Delta.pdf?raw=true)

Fig. 6: Top: Estimated and filtered heading difference and interpolated reference value for the middle finger during the first experiment. Bottom: Relative orientation error.

### Index finger, second experiment

[![](/files/2dof/2DoF_Joint_Heading_Tracking_Exp2_F2_Cost.jpg)](./files/2dof/2DoF_Joint_Heading_Tracking_Exp2_F2_Cost.pdf?raw=true)

Fig. 7: Cost function for the index finger during the second experiment.

[![](/files/2dof/2DoF_Joint_Heading_Tracking_Exp2_F2_Delta.jpg)](./files/2dof/2DoF_Joint_Heading_Tracking_Exp2_F2_Delta.pdf?raw=true)

Fig. 8: Top: Estimated and filtered heading difference and interpolated reference value for the index finger during the second experiment. Bottom: Relative orientation error.

### Middle finger, second experiment

[![](/files/2dof/2DoF_Joint_Heading_Tracking_Exp2_F3_Cost.jpg)](./files/2dof/2DoF_Joint_Heading_Tracking_Exp2_F3_Cost.pdf?raw=true)

Fig. 9: Cost function for the middle finger during the second experiment.

[![](/files/2dof/2DoF_Joint_Heading_Tracking_Exp2_F3_Delta.jpg)](./files/2dof/2DoF_Joint_Heading_Tracking_Exp2_F3_Delta.pdf?raw=true)

Fig. 10: Top: Estimated and filtered heading difference and interpolated reference value for the middle finger during the second experiment. Bottom: Relative orientation error.
