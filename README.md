# Vehicle Lateral Control using PID and MPC

This project is a **learning-focused simulation** of vehicle lateral control
using **PID** and **Model Predictive Control (MPC)** implemented in Python.

The goal is to control the steering angle of a vehicle so that it follows
a desired lateral trajectory while minimizing yaw and lateral position error.

---

## 🚗 Project Overview

- Vehicle modeled using a simplified **bicycle model**
- Steering angle is the control input
- Controller minimizes lateral deviation from a reference path
- PID and MPC controllers can be compared

This type of control problem is commonly studied in:
- Control Systems
- Autonomous Vehicles
- Robotics
- Advanced Driver Assistance Systems (ADAS)

---

## 📂 Repository Structure

- `MAIN_MPC_car_lateral.py`  
  Main simulation script. Runs the controller, updates vehicle states,
  and generates plots and animations.

- `support_files_car.py`  
  Helper functions and vehicle dynamics used by the main simulation.

- `results/`  
  Stores output plots and simulation results.

- `requirements.txt`  
  Python dependencies (NumPy, Matplotlib).

---

## 🧠 Control Methods

### PID Control
The PID controller computes steering input as:


