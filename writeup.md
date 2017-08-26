# writeup

## The Model

* The kinematic model is used.

* states
  * x, y : position of the vehicle
  * psi : direction
  * v : speed
  * cte : cross tracking error
  * espi : direction error
  
* actuators
  * delta : truning rate
  * a : acceleration rate
  
* update equations

![update equations](writeup_update_equations.png =400x)

## Timestep Length and Elapsed Duration (N & dt)

* I used quizzes values (N & dt)

## Polynomial Fitting and MPC Preprocessing

* preprocesses transformed to car coordinate system
* polynomial is fitted to the points.

## Model Predictive Control with Latency

* I used 100 millisecond latency.