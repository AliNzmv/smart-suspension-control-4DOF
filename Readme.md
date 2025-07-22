# 🚗 Intelligent Control & Fault Diagnosis of a 4-DOF Vehicle Suspension System

This repository contains the simulation and implementation of intelligent control and identification methods for a **4-degree-of-freedom (4-DOF) advanced vehicle suspension system** using neural networks and reinforcement learning techniques.

## 📘 Project Summary

The project investigates different neural architectures (MLP, RBF, LSTM) and reinforcement learning (SAC) for:

- 🧠 System identification
- 🎯 Control design
- ⚠️ Fault diagnosis

The goal is to improve **ride comfort**, **system stability**, and **adaptive response** to nonlinear road disturbances.

## 🧩 System Description

- **Model Type:** Nonlinear suspension system with 4 DOF
- **Key components:** Sprung mass, unsprung mass, nonlinear spring and damper, tire dynamics
- **Nonlinearity:** Modeled with 2nd/3rd order stiffness and damping
- **Inputs:** Road disturbance, control force
- **Outputs:** Displacements, velocities, accelerations, tire and suspension forces

## 🧪 Implemented Methods

### 🔹 Multi-Layer Perceptron (MLP)

- Identification of system dynamics
- Direct & indirect control designs
- Good performance in stable tracking

### 🔸 Radial Basis Function (RBF)

- Nonlinear system identification
- Sensitive to sample rate
- Effective for steady-state estimation

### 🔷 Long Short-Term Memory (LSTM)

- Time-series modeling for dynamic systems
- Observers for hidden state reconstruction
- Struggled with stability and generalization

### 🟢 Soft Actor-Critic (SAC)

- Model-free RL-based controller
- Designed for high-dimensional, continuous control
- Adaptive and robust in stochastic conditions

## 🧠 Requirements

- Python 3.9+
- NumPy
- TensorFlow or PyTorch
- Matplotlib
- Gym (for RL integration)
