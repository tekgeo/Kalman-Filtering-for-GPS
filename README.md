# Kalman Filter for GPS Trajectory Estimation

**Academic Exercise** | Positioning and Location-Based Services Course from Politecnico di Milano - MSc Geoinfromatics engineering

Python implementation of a Kalman Filter to estimate position and velocity from noisy GPS observations. This project demonstrates recursive state estimation and filtering techniques for trajectory smoothing.

### Problem Statement

**Given**:
- 2D trajectory of a moving body [X, Y]
- Noisy GPS observations (σ_obs = 25m)
- Assumption: Constant velocity motion model
- Time interval between observations: Δt = 1.0 second

**Task**:
- Implement a Kalman Filter to estimate true position and velocity
- Filter noisy observations to reconstruct smooth trajectory
- Track position (X, Y) and velocity (Vx, Vy) over time
- Visualize observed vs. estimated positions

##  Kalman Filter Theory

The Kalman Filter is a mathematical method used to estimate the state of a system (like position, speed, or temperature) over time, even when measurements are noisy or uncertain. It combines predictions from a model with actual measurements to produce a more accurate estimate.
