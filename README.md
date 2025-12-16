# Reflex-Bin-CV
This project focuses on developing an Autonomous Mobile Robot (AMR) capable of detecting, tracking, and physically "catching" trash thrown towards it in mid-air. Unlike traditional smart bins that simply open a lid, this system uses an upward-facing camera and Computer Vision (OpenCV) to predict the trajectory of falling objects. 
The robot utilizes a holonomic drive system (Mecanum/Omni wheels) to move instantly in any direction without turning, ensuring it reaches the landing spot before the object hits the ground.  
Key FeaturesReal-Time  Object Tracking: Uses a high-speed upward-facing camera to track objects against the ceiling background.
Trajectory Prediction: Implements physics-based algorithms (Kalman Filter/Linear Regression) to calculate the "Time to Impact" and landing coordinates based on the object's expansion rate (Z-axis velocity).
Holonomic Mobility: Designed for a chassis with Mecanum wheels, allowing for omnidirectional movement (strafing) for rapid positioning.
Simulation-First Approach: Includes a robust Software-in-the-Loop (SIL) simulation built in Pygame to test control logic and tracking algorithms before hardware deployment.
