# 2D Controller for CARLA Waypoint Follower 🚗

This repository contains a **2D vehicle controller** implemented in Python for the [CARLA Simulator](https://carla.org/).  
The controller uses:

- **PID control** for longitudinal dynamics (throttle & brake)  
- **Pure Pursuit** for lateral dynamics (steering)  

It is designed to follow a list of waypoints, each with an `(x, y, desired_speed)` format.


