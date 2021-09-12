## Sotaro Katayama

I'm a Ph. D. student in Integrated Dynamical Systems Lab([English](http://www.ids.sys.i.kyoto-u.ac.jp/index_e.html)/[Japanese](http://www.ids.sys.i.kyoto-u.ac.jp/)) advised by Prof. Toshiyuki Ohtsuka. 
My research lies on optimization-based control and planning of robotic systems, especially modle predictive control (MPC) for legged robotics. 
I'm also interested in algorithms and theoretical analysis (e.g., stability) of MPC, including MPC for switched systems. 

## Education
- Kyoto University, 2020 - Present  
Ph.D student

- Graduate School of Informatics, Kyoto University, 2013 - 2017  
Master of Informatics

- Kyoto University, 2013 - 2017  
Bachelor of Engineering Science

## Work Experience
- Hitachi, Ltd., R&D, 2020-2021

## Publications

## Open Source Softwares
- [idocp](https://github.com/mayataka/idocp)  
This is a collection of the very efficient optimal control problem solvers for multibody robots with/without contacts, e.g., for robot manipulators and legged robots.
There are example implementations for [ROS](https://github.com/mayataka/crane_x7_mpc)/[ROS2](https://github.com/mayataka/crane_x7_mpc_ros2) using ron_control/ros2_control for RT corpolation's robot manipulator CRANE-X7.

- [autogenu-jupyter](https://github.com/mayataka/autogenu-jupyter)  
This is a code generation tool for MPC with the continuous/GMRES-type algorithms.
The major differences from the [Maple-version] are: 1) jupyter-based code generation, 2) Fischer-Burumeister function for inequality constraints, 3) the multiple-shooting variant of the continuous/GMRE method.

- [DDPCodeGen](https://github.com/mayataka/DDPCodeGen)
This is a code generation tool for differential dynamic programming, based on the code-generation system of autogenu-jupyter.
