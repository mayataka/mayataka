## Sotaro Katayama

I'm a Ph. D. student in Integrated Dynamical Systems Lab([English](http://www.ids.sys.i.kyoto-u.ac.jp/index_e.html)/[Japanese](http://www.ids.sys.i.kyoto-u.ac.jp/)) advised by Prof. Toshiyuki Ohtsuka. 
My research lies on optimization-based control and planning of robotic systems, especially modle predictive control (MPC) for legged robotics. 
I'm also interested in algorithms and theoretical analysis (e.g., stability) of MPC, including MPC for switched systems. 

## Education
- Kyoto University, 2019 - Present  
Ph.D student

- Graduate School of Informatics, Kyoto University, 2017 - 2019  
Master of Informatics

- Kyoto University, 2013 - 2017  
Bachelor of Engineering Science

## Work Experience
- Hitachi, Ltd., R&D, 2019-2020

## Publications
- <u>S. Katayama</u>, T. Ohtsuka, "Lifted contact dynamics for efficient direct optimal control of rigid body systems with contacts," [arXiv preprint arXiv:2108.01781](https://arxiv.org/abs/2108.01781)
- <u>S. Katayama</u>, T. Ohtsuka, "Efficient Riccati recursion for optimal control problems with pure-state equality constraints," [arXiv:2102.09731](https://arxiv.org/abs/2102.09731)
- <u>S. Katayama</u>, T. Ohtsuka, "Inverse dynamics‐based formulation of finite horizon optimal control problems for rigid‐body system," *Optimal Control Applications and Methods*, pp. 1-19, 2021, https://doi.org/10.1002/oca.2750  
- <u>S. Katayama</u>, T. Ohtsuka, "Riccati recursion for optimal control problems of nonlinear switched systems," IFAC Conference on Nonlinear Model Predictive Control 2021 (NMPC 2021), 2021 ([arXiv:2102.02065](https://arxiv.org/abs/2102.02065))  
- <u>S. Katayama</u>, T. Ohtsuka, "Efficient solution method based on inverse dynamics for optimal control problems of rigid body systems," IEEE International Conference on Robotics and Automation 2021 (ICRA 2021), 2021 ([arXiv:2106.04176](https://arxiv.org/abs/2106.04176))
- S. Katayama, T. Ohtsuka, "Efficient solution method based on inverse dynamics of optimal control problems for fixed-based rigid-body systems," IFAC World Congress 2020, Vol. 53, No. 2, pp. 6483-6489, 2020, https://doi.org/10.1016/j.ifacol.2020.12.1794
- S. Katayama, T. Ohtsuka, "Automatic code generation tool for nonlinear model predictive control with Jupyter," IFAC World Congress 2020, Vol. 53, No. 2, pp. 7033-7040, https://doi.org/10.1016/j.ifacol.2020.12.447
- S. Katayama, M. Doi, T. Ohtsuka, "A moving switching sequence approach for nonlinear model predictive control of switched systems with state-dependent switches and state jumps," *International Journal of Robust and Nonlinear Control*, Vol. 30, No.2, pp. 719-740, 2020, https://doi.org/10.1002/rnc.4804
 

## Open Source Softwares
- [idocp](https://github.com/mayataka/idocp)  
This is a collection of the very efficient optimal control problem solvers for multibody robots with/without contacts, e.g., for robot manipulators and legged robots.
  - [crane_x7_mpc_ros2](https://github.com/mayataka/crane_x7_mpc_ros2)  
  This is an example imepelemtation of MPC for RT corpolation's robot manipulator CRANE-X7 on ROS2 using ros2_control.   
  - [crane_x7_mpc](https://github.com/mayataka/crane_x7_mpc)  
  This is ROS1 version using ros_control

- [SwitchedOCP.jl](https://github.com/mayataka/SwitchedOCP.jl)  
This is an optimal control solver for switched systems on Julia.

- [autogenu-jupyter](https://github.com/mayataka/autogenu-jupyter)  
This is a code generation tool for MPC with the continuous/GMRES-type algorithms.
The major differences from the [Maple-version] are: 1) jupyter-based code generation, 2) Fischer-Burumeister function for inequality constraints, 3) the multiple-shooting variant of the continuous/GMRE method.

- [DDPCodeGen](https://github.com/mayataka/DDPCodeGen)  
This is a code generation tool for differential dynamic programming, based on the code-generation system of autogenu-jupyter.
