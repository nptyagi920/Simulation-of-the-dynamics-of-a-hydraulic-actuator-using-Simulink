# Simulation-of-the-dynamics-of-a-hydraulic-actuator-using-Simulink
A hydraulic actuator connected to an inertial load of mass, M = 1000Kg with both the inlet and outlet ports of the cylinder in closed condition. Both the chambers of the cylinder are having trapped hydraulic fluid pressurized to an initial value of Po. The parameter values of the actuator are given below:

• Area of cross section of the piston , Ap = 20.44x10-4m^2

• Bulk modulus of hydraulic fluid, = 9.81x108Pa

• Half volume of the hydraulic cylinder, Vo = 1.063x10-4m^3

• Initial pressure of both hydraulic chambers, P1(0) = P2(0) = Po = 1x107Pa

• Initial values of actuator position and velocity, Xp(0) = X˙p(0) = 0

• Cross port leakage coefficient, CL=0.


**Description of system dynamics**


![image](https://user-images.githubusercontent.com/66457607/137451158-bb93c648-c064-482d-87d2-3ce23a83109c.png)

**Steps for Using the files:**
1. Run the paramers.m file
2. Run the Hydraulic_Actuator.slx file
3. Plot the graphs to observe the amplitude and period of oscillation of Pl(t) using plot.m file
