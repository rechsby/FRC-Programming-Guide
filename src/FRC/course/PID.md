# PID


The PID controller is a common *feedback* controller consisting of 3 terms: proportional, integral, and derivative. You don't need to know what an integral/derivative is or how it works, only that they are used in PID controllers.

## Why?
It's important to understand that when we're interfacing with electrical components (in this case, motors) the motor has no idea how to get to a certain speed or position. All the motor can do is take a given voltage and convert it to rotational speed. We need a PID controller to be able to set a motor's position or speed *instead* of an instantaneous voltage that's sent to the motor.

Some common examples of when to use a PID controller include:
- Controlling the speed / position of a motor
- Controlling the heading of a robot

> A feedback controller refers to a controller that *responds* to interference (error), we'll cover controllers that can *predict* interference before it happens


We'll explain PID controllers by going through each term individually, building off the term before it.


## Important Terms

Before explaining each term, keep in mind these definitions:
- Setpoint: Where the PID controller wants to be; it's goal.
- Output: Slightly counterintuitive, the Output is the current value of the controller's current state. The motor's **current** position, voltage, etc.
- Error: Error is defined as the difference between the Output and the Setpoint.
- Control Effort: The current output of the PID controller, when controlling a motor this is usually a voltage that is then sent to the motor.

## The Proportional Term

The Proportional term attempts to drive the position error to zero by contributing to the control signal proportionally to the current position error. Intuitively, this tries to move the output towards the reference.