* Which reference path is the **most compact** and **easy to construct**?

    - Track straight line segments
    
* What is the most **ACCURATE** and **PRECISE** definition of the crosstrack error?

    - The crosstrack error is the distance between the vehicle reference point and the closest point on the reference 
    path
    
* What vehicle reference frame is used in a **pure pursuit controller**?

    - Center of rear axle
    
* **Compute the radius** from the instantaneous center of rotation to the center of the vehicle rear axle (in m) 
required for an autonomous vehicle to follow the desired path based on the information below.
    
    The lookahead distance is 10 m; the car length is 4 m; the angle between the vehicle’s body heading and the 
    lookahead line is 30 degrees. Your answer should be an integer.

    - 10
    
* **Compute the steering angle (in degrees)** required for an autonomous vehicle with pure pursuit lateral control 
for following the desired path based on the information below.

    The lookahead distance is 15 m; the car length is 5 m; the angle between the vehicle’s body heading and 
the lookahead line is 60 degrees.
    
    - 30
    
* Consider a situation in which a vehicle traveling speed has decreased from 100 km/h to 50 km/h. This vehicle 
lateral control is implemented with a pure pursuit controller where `l_d` is assigned as a function of vehicle speed. 
**How should `l_d` change in this situation**?

    - `l_d` should decrease
    
* What are **major components** of the Stanley controller? (Select all that apply)

    - Proportional control is introduced for minimizing the crosstrack error
    - Steering angle command is restricted to the min and max steering angles
    - Steering angle is set equal to the heading direction to eliminate heading error relative to the path
    
* **What is the correct figure** of the crosstrack error dynamics for a small error value(where `e'(t)=-ke(t)`)?

    - Figure 3
    
* What is the value of the crosstrack error, governed by the ODE `e'(t)=-ke(t)` at `t=2`, given that `e(0)=4` and `k=1`?
Please give your answer with the precision of 2 decimal places.
    
    - 0.54
    
* Which of the statements below about Model Predictive Control (MPC) are **TRUE**? (Select all that apply)

    - MPC can impose constraints on the states and the input simultaneously
    - The formulation of an MPC controller is straightforward
    - MPC works for both linear and nonlinear models
    
* What is the typical way of finding the solution for a **nonlinear vehicle dynamics model** given an input function?

    - Numerical optimization
    
* What is the output of the **Model Predictive Controller** described in this course? (Select all that apply)

    - Longitudinal forces
    - Lateral forces