# Drone Control System

## Overview
This project focuses on **control of a drone system**. The system was modeled and linearized, and a **state-feedback controller** was designed based on the linearized model. **Optimal control** was implemented using a **state-feedback LQR controller**, and a **Kalman filter** was developed to improve state estimation and enhance overall system performance. The LQR and Kalman filter were combined as an **observer-based controller** and applied to the linear system for robust stabilization.

## Features
- Nonlinear system modeling and linearization  
- **State-feedback controller** designed on the linear model and applied to the nonlinear system  
- Optimal control via **LQR (Linear Quadratic Regulator)**  
- **Kalman filter** for improved state estimation  
- Observer-based control implementation  

## Project Structure

The project is divided into **two parts**, each in its own folder:  

1. **Part A – Modeling, Linearization, and Controller Design**  
   - Open the folder **PartA** in MATLAB (or your environment).  
   - Run the main script:  
     ```matlab
     run('main.m')
     ```
   - This part performs system modeling, linearization, and state-feedback controller design.  

2. **Part B – Optimization and Observer-Based Control**  
   - Open the folder **PartB** in MATLAB (or your environment).  
   - Run the main script:  
     ```matlab
     run('main.m')
     ```
   - This part applies the **LQR design alone (without and with noise), the Kalman filter design, and then combines them as an observer-based controller** to the linear system, and performs optimization to improve overall system performance.
