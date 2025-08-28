# 2D Controller for CARLA Waypoint Follower 🚗

This repository contains a **2D vehicle controller** implemented in Python for the [CARLA Simulator](https://carla.org/).  
The controller uses:

- **PID control** for longitudinal dynamics (throttle & brake)  
- **Pure Pursuit** for lateral dynamics (steering)  

It is designed to follow a list of waypoints, each with an `(x, y, desired_speed)` format.

![brake_output](https://github.com/GrandEchoWhiskey/uot-self_driving_cars-labs/blob/main/Course1FinalProject/controller_output/brake_output.png)
![forward speed](https://github.com/GrandEchoWhiskey/uot-self_driving_cars-labs/blob/main/Course1FinalProject/controller_output/forward_speed.png)
![steer output](https://github.com/GrandEchoWhiskey/uot-self_driving_cars-labs/blob/main/Course1FinalProject/controller_output/steer_output.png)
![throttle output](https://github.com/GrandEchoWhiskey/uot-self_driving_cars-labs/blob/main/Course1FinalProject/controller_output/throttle_output.png)
![trajectory](https://github.com/GrandEchoWhiskey/uot-self_driving_cars-labs/blob/main/Course1FinalProject/controller_output/trajectory.png)
