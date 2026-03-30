# NumPy to PointCloud2 (ROS2)

## Overview
Implemented code that subscribed to a ROS2 Node containing NumPy arrays in the format of [x-coordinate, y-coordinate, z-coordinate, cluster number] 

## Tech Used
- Python
- Foxy ROS2
- NumPy
- RViz2
- MobaXTerm
- 20.04 Ubuntu

## Features

## Visualization of Results
<img width="1919" height="1132" alt="Screenshot 2026-03-29 162814" src="https://github.com/user-attachments/assets/cfd8eca6-327f-4990-9e8b-634d175a62a9" />

## What I learned

points_to_pc2.py in the folder my_pkg contains the actual code for subscribing to numpy arrays in the form of [x, y, z, cluster#] and publishing CloudPoint2 data for rviz2. The rest of the files were just made to help create points_to_pc2.py
