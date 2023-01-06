# Quadcopter-Control-using-an-Inverted-Pendulum-Model

## The upshot of Hover stabilization control used.

This repository simulates a quadcopter that uses a dynamic approximation of being an inverted pendulum and uses PID control to stabilize the pendulum in the hover position. The control signal is calculated using a feedforward term that accounts for the force required to balance the pendulum under the influence of gravity, a proportional term that corrects for any error in the position of the pendulum, an integral term that helps to eliminate steady-state error, and a derivative term that improves the response of the system. The control signal is then low-pass filtered to remove noise. The state of the system (the angle and angular velocity of the pendulum) is updated at each time step using the control signal, and the results are plotted.
