# Attitude Determination Algorithm

## Background
- The attitude (or orientation) of a CubeSat can be described in a few different forms: rotation matrix, Euler Angles, quaternions
- These forms of parameterization each have their strengths and weaknesses (e.g. computing efficiency, avoiding gimbal lock)
- To parameterize attitude, various methods have been formulated.
- There are typically two steps of attitude determination: 1) Attitude Initialisation. 2) Recursive methods for Attitude Estimation
- Some of these methods include: TRIAD Algorithm, Davenport's Q-method, Complimentary Filter, Extended Kalman Filter, Quaternion Estimation Algorithm (QUEST)
- This project is suitable for someone with a strong foundation in linear algebra, isn't afraid of maths and likes tackling complex problems.
  
## Project Objectives
- Do a literature review of attitude determination algorithms, evaluating which method/s are most feasible for our CubeSat.
- Simulate the algorithm/s, with simulated noise in sensor data, to analyse the algorithm's performance and show as a proof of concept (using MATLAB).
- - OR write pseudo-code of the algorithm, assuming sensor data is being obtained.
- Create a block diagram of proposed Attitude determination Algorithm/s, clearly explaining each step, including relavent equations.
- An extension of this project can be looking into attitude control laws to get from current attude to desired attitude.

## Resources to get you started
- For background knowledge: [Dr Shane Ross (THE GOAT)](https://www.youtube.com/watch?v=HCd-leV8OkU&t=1266s) - his videos on rigid body kinematics also introduce the
  concept of attitude really well.
- Need to put more sources here lol
