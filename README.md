# MotionControl
Control software for the manupulation of a robotic arm through the use of Kinect Sensor

Using the Mirosoft Kinect Sensor, the position and orientation of the skeletal joints present in the right arm, are tracked and used to determine the necessary angles to be applied to the motor components of a Kawasaki robotic arm, in order to mimic human controller's arm position.

These joint orientations are then used to build AS commands that can be sent to the robot through am ethernet cable (via telnet connection), allowing for intuitive motion control of the the robot arm.
