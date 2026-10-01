# Robotics Initiative by Srushti Technologies: Day 01

**Topic:** Robot components and degrees of freedom

## 1. Robot components (Sense, Think, Act)
- Sensors convert the environment into signals.
- The controller (Arduino, PLC) processes them and decides.
- Actuators produce movement.
- Closed-loop feedback: the robot compares the commanded result with the measured one and corrects the error.

## 2. Degrees of freedom of a rigid body
- DOF = number of independent values needed to describe a configuration.
- A planar rigid body (a coin on a table) has 3 DOF.
- A spatial rigid body has 6 DOF: position (x, y, z) and orientation (roll, pitch, yaw).
- General rule: DOF = (sum of freedoms of the bodies) - (independent constraints).

## 3. Degrees of freedom of a robot
- Robots are rigid links connected by joints.
- Joints add constraints and reduce freedom (a hinged door has 1 DOF instead of 6).
- Revolute joint: rotates. Prismatic joint: slides.
- A robot's DOF can be counted from its number of links and joints.

## 4. Rigid-body motions and rotation matrices
- A rotation matrix R is a 3x3 matrix describing orientation.
- 9 numbers but only 3 independent (6 constraints).
- Columns are the body's axes written in the fixed frame.
- R^T * R = I, so the inverse of R is its transpose, and det(R) = +1.
- Uses: represent orientation, change reference frame, rotate a vector.


*Part of the Robotics Initiative by Srushti Technologies, Day 01.*# Day-1