
# Autonomous Vehicle Driver

## Overview

This repository contains a collection of Python scripts that collectively form an autonomous vehicle driver. Each script serves a specific purpose and contributes to the overall functionality of the autonomous vehicle system. The scripts include modules for basic agent behavior, constant velocity control, global route planning, local planning, sensor data processing, and visualization.

## Files

1. **basic_agent.py**
   - This script defines the basic behavior of the autonomous vehicle, including high-level decision-making and interactions with the environment.

2. **behavior_agent.py**
   - The behavior agent script refines the behavior of the autonomous vehicle, focusing on specific driving scenarios and response strategies.

3. **constant_velocity_agent.py**
   - Implements a basic constant velocity control strategy for the autonomous vehicle.

4. **global_route_planner.py**
   - Utilizes global information to plan the optimal route for the vehicle, taking into account waypoints, maps, and destination points.

5. **local_planner.py**
   - Focuses on short-term planning and navigation, making real-time decisions based on immediate sensor input and the global route plan.

6. **lidar_to_camera.py**
   - Converts Lidar data to camera-compatible format, facilitating the integration of different sensor inputs.

7. **open3d_lidar.py**
   - Utilizes the Open3D library to process and visualize Lidar data, enhancing the understanding of the vehicle's surroundings.

8. **sensor_synchronization.py**
   - Manages the synchronization of data from various sensors, ensuring accurate and coherent information for decision-making.

9. **visualize_multiple_sensors.py**
   - Combines and visualizes data from multiple sensors, providing a comprehensive view of the vehicle's environment.

10. **automatic_control.py**
    - Implements automatic control mechanisms, allowing the vehicle to execute planned actions based on sensor data and decision-making algorithms.

## Dependencies

Ensure that the following dependencies are installed before running the scripts:

- Python (>=3.6)
- [Open3D](http://www.open3d.org/) library
- Other dependencies as specified in individual script comments or documentation.
