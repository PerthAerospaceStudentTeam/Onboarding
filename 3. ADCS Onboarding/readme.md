# ADCS Onboarding

The Attitude Determination and Control System (ADCS) Department works on all the system design, software and hardware to determine
and control the orientation of the CubeSat. This involves interfacing with sensors and actuators, algorithm design, simulations and
testing. ADCS is critical to stabilising the satellite, optimising solar power, establishing communications and point payloads.

You do not need to know the intricacies of ADCS to work on ADCS projects, as you would be working on hardware or testing, but it
is still important to know the key ideas.

## Background
- Attitude = Orientation
- Orientation is a transformation between a fixed reference frame (usually earth) to a body-fixed frame (CubeSat).
  It can be parameterized by Euler angles, Direction-Cosine Matrices or Quaternions.
- Sensors are used provide vectors (sun vector, magnetic field vector) in the body-fixed frame. These vectors are compared to the
  vectors as determined from the fixed reference frame (Earth) to get relative orientation.
- Attitude sensors typically used are magnetometers, sun sensors, angular rate sensors, star-trackers, and horizon sensors.
- Actuation methods for attitude control include Magnetorquers and Reaction Wheels.
- Magnetorquers are variable electromagnets that interact with the earth's magnetic field to produce control torques.
- ADCS has some operational modes: Detumbling, Nadir Pointing (Mission dependant), Sun Tracking

## ADCS Resources
