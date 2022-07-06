# PickAndPlace

## Description
In this project, We utilized a 6 DOF industrial robotic arm, UR5 to pick and place small known objects, similar to bin picking process. The project starts with the theoretical calculation of Forward Kinematics and Inverse Kinematics of UR5. With the assumption of slow movement of the joints, Dynamics of the arm were neglected. We used MATLAB and Vrep to demonstrate the simulation of my project. Practical implementation begins with making Vrep and MATLAB communicate to each other. We used MATLAB as the scripting language to implement FK and IK. Once, Vrep and MATLAB were setup, We validated my implementation using theoretical FK and IK events and matching them with Vrep Output. In the end, We have demonstrated the pick & place operation with the robot tasked to segregate between different blocks and placing them on different tables.


## Installing Supporting Libraries

If Robotics Toolbox is not already installed on your MATLAB, you will need to install it.
You can do it directly within the MATLAB software or follow the following steps to install it locally.

1. Inside the Main Folder, you will find RoboticsToolbox_installation Folder containing RoboticsToolboxforMATLAB.mltbx
2. From Matlab Software, open this file and click accept & install on prompt.
3. Robotics Toolbox will be installed.

## Instructions to Simulate

1. Unzip the contents of the project.
2. Go to Main Folder and open PickAndPlace.m script in MATLAB editor.
3. Open UR5Pick&Place.ttt in Vrep Software.
4. Run Simulation on Vrep Software.
5. Execute PickAndPlace.m script on MATLAB.
6. After MATLAB script finishes run, you can stop Vrep Software.
