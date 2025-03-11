
# Autonomous Drone Navigation and Control using MATLAB

This project focuses on simulating and testing autonomous drone navigation and control algorithms using MATLAB and Simulink. It includes various simulation models for path planning, orbit-following, waypoint navigation, and environment perception (depth and semantic segmentation). The project supports both **fixed-wing** and **multirotor** drones, with 3D animations and graphical visualizations for real-time monitoring.

---

## Project Structure

The project consists of the following MATLAB/Simulink files:

1. **`orbitfollower3Danimation.slx`**  
   - Simulates a drone following a circular or elliptical orbit in 3D space with animation.

2. **`Depth and semantic segmentation.slx`**  
   - Processes depth data and semantic segmentation for obstacle detection and environment understanding.

3. **`uav_animationwithoutslider.slx`**  
   - Simulates UAV animation without a slider interface for basic movement testing.

4. **`waypointGraph.slx`**  
   - Implements waypoint-based navigation, where the drone follows a predefined set of waypoints.

5. **`FixedWing.slx`**  
   - Simulates fixed-wing drone dynamics and control algorithms.

6. **`lowfidelitymultirotor_guidanceGraph.slx`**  
   - A low-fidelity simulation for multirotor drones, focusing on guidance algorithms (e.g., path following).

7. **`orbitfollower_uavanimationGraphical.slx`**  
   - Simulates orbit-following behavior with enhanced graphical visualization for UAV animation.

8. **`uavanimation_slider.slx`**  
   - Simulates UAV animation with a slider interface for real-time parameter adjustments.

9. **Implementation Videos**  
  
**1st**
https://github.com/user-attachments/assets/7b192226-00ca-4853-a73e-b2203e39078e

---

**2nd**
https://github.com/user-attachments/assets/f15fd7ec-b7ec-44c8-952d-10c25296fc9d
---
**3rd**


https://github.com/user-attachments/assets/531c2eee-d0f0-4a5a-9bf3-1066682dc660

---
**4th**


https://github.com/user-attachments/assets/248f8fd7-5010-478d-8fa8-719677fb4842
---
**5th**



https://github.com/user-attachments/assets/0c9df7f4-8950-43a4-9df8-760e17821b01


---

## Requirements

To run this project, ensure you have the following installed:
- **MATLAB R2020a or later** (with Simulink).
- **Aerospace Toolbox** (for UAV simulations).
- **Computer Vision Toolbox** (for depth and semantic segmentation).
- **3D Animation Toolbox** (for visualizing drone movements).

---

## How to Run the Simulations

1. **Clone or download the repository** to your local machine.
2. Open MATLAB and navigate to the project directory.
3. Open the desired `.slx` file in Simulink (e.g., `orbitfollower3Danimation.slx`).
4. Click the **Run** button in Simulink to start the simulation.
5. Use the **slider interface** (if available) to adjust parameters in real-time.
6. View the **3D animations** and **graphs** to analyze the drone's performance.

---

## Key Features

- **Path Planning and Waypoint Navigation**:  
   - Implemented in `waypointGraph.slx` for predefined path following.

- **Orbit-Following Behavior**:  
   - Simulated in `orbitfollower3Danimation.slx` and `orbitfollower_uavanimationGraphical.slx`.

- **Environment Perception**:  
   - Depth and semantic segmentation for obstacle detection in `Depth and semantic segmentation.slx`.

- **Fixed-Wing and Multirotor Simulations**:  
   - Separate models for fixed-wing (`FixedWing.slx`) and multirotor (`lowfidelitymultirotor_guidanceGraph.slx`) drones.

- **3D Animations and Visualizations**:  
   - Real-time monitoring of drone movements in `uav_animationwithoutslider.slx` and `uavanimation_slider.slx`.

---

## Example Workflow

1. Start with `waypointGraph.slx` to define a set of waypoints for the drone to follow.
2. Use `lowfidelitymultirotor_guidanceGraph.slx` to test guidance algorithms for multirotor drones.
3. Visualize the drone's path and performance using `uavanimation_slider.slx`.
4. For orbit-following behavior, run `orbitfollower3Danimation.slx` and analyze the 3D animation.

---

## Results

The project includes **images** and **graphs** showcasing the drone's performance, such as:
- 3D animations of drone movements.
- Graphs of position error, velocity, and control inputs.
- Visualizations of depth and semantic segmentation for environment perception.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For questions or feedback, please contact:  
**Biswajit Behera

Uploading lab 511.mp4…

** 

 
**Email:** your.email@example.com  
**GitHub:** [Your GitHub Profile](https://github.com/yourusername)

---

This README provides a clear and concise overview of your project, making it easy for others to understand and use. Let me know if you’d like to customize it further!
