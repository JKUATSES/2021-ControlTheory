# 2021-ControlTheory
This is Control theory for ses projects weekly meetings during the academic year 2021-20221  
It covers:   
           1) Introduction into control systems  
           2) Types of control systems  
           3) PID control  
           4)State Space represenation   
           5) Drone control (example)  
           6) Self balancing robot (example)  
           7) adaptive cruise control (example)  
           # Summary  
           A control system can be deined as a system which controls other systems. Examples of control systems in your day-to-day life include an air conditioner, a refrigerator, an air conditioner, a bathroom toilet tank, an automatic iron, and many processes within a car – such as cruise control.  
           The main feature of a control system is that there should be a clear mathematical relationship between the input and output of the system.  
           A good control system should be: accurate, sensitive, stable, fast, and have a large bandwidth.  
           There are two types of control systems: closed loop and open loop control systems.  
           An open-loop control system (also known as a non-feedback system) acts completely on the basis of input; the output has no effect on the control action.  
           A closed-loop control system looks at the current output and alters it to the desired condition; also known as a feedback system. The control action in these systems is based on the output.  
           A proportional–integral–derivative controller (PID controller or three-term controller) is a control loop mechanism employing feedback that is widely used in industrial control systems and a variety of other applications requiring continuously modulated control. A PID controller continuously calculates an error value as the difference between a desired setpoint and a measured process variable and applies a correction based on proportional, integral, and derivative terms (denoted P, I, and D respectively), hence the name. The working principle behind a PID controller is that the proportional, integral and derivative terms must be individually adjusted or "tuned." Based on the difference between these values a correction factor is calculated and applied to the input. Drones are one of the most prominent examples of PID control and a good way to understand how it works. Drones use PID control in flight to control their position, and the driver should tune it right to get a smooth ride.  
           Self-balancing robot is a two-wheeled robot which balances itself so that it prevents itself from falling. This balance can be achieved using PID control. 
           In control engineering, a state-space representation is a mathematical model of a physical system as a set of input, output and state variables related by first-order differential equations or difference equations. State variables are variables whose values evolve over time in a way that depends on the values they have at any given time and on the externally imposed values of input variables. Output variables’ values depend on the values of the state variables. Thus, the state space of a dynamical system is the set of all possible states of the system. Each coordinate is a state variable, and the values of all the state variables completely describes the state of the system. It differs from transfer function in that a transfer function is not defined for nonlinear systems, and thus can only describe linear systems and a state space model can describe both.  
           The state space representation of a system is given by two equations :  
           q(t)=Aq(t) + Bu(t)  
           y(t)=Cq(t) + Du(t)  
           The first equation is called the state equation, the second equation is called the output equation.  For an nth order system (i.e., it can be represented by an nth order differential equation) with r inputs and m outputs the size of each of the matrices is as follows:

q is nx1 (n rows by 1 column); q is called the state vector, it is a function of time
A is nxn; A is the state matrix, a constant
B is nxr; B is the input matrix, a constant
u is rx1; u is the input, a function of time
C is mxn; C is the output matrix, a constant
D is mxr; D is the direct transition (or feedthrough) matrix, a constant
y is mx1; y is the output, a function of time  
Fuzzy logic is widely used in machine control. The term "fuzzy" refers to the fact that the logic involved can deal with concepts that cannot be expressed as the "true" or "false" but rather as "partially true". Fuzzy logic provides a way of dealing with imprecision and nonlinearity in complex control situations.

 Resources:  
           Types of contro systems: https://www.electrical4u.com/control-system-closed-loop-open-loop-control-system/  
           Introduction to control systems: https://www.tutorialspoint.com/control_systems/control_systems_introduction.htm  
           State space represenbtation and controllability: https://www.vssut.ac.in/lecture_notes/lecture1450172554.pdf  
           Thrust vector control for rockets using PID: https://www.youtube.com/watch?v=4cw9K9yuIyU  
           Drone flight dynamics: https://www.youtube.com/watch?v=C0KBu2ihp-s&t=4s  
           PID control tuning for self balancing robots: https://www.youtube.com/watch?v=uyHdyF0_BFo  
           Inverted pendulum on a cart demostartion: https://www.youtube.com/watch?v=AuAZ5zOP0yQ  
           Control system design for autonomous cars: https://www.youtube.com/watch?v=pSxaOWiIyCU  
           Adaptive cruise control: https://www.youtube.com/watch?v=8pMzaatc3Eg    
           Adaptive Cruise Control Project Using MATLAB and Arduino Uno Board: https://www.youtube.com/watch?v=LEmP7HJF_OE  
           Introduction to fuzzy logic: https://www.youtube.com/watch?v=rln_kZbYaWc    
