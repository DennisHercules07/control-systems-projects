# 01_self_balancing_robot

**Brief:** Simulation and controller design for a two-wheel self-balancing robot (inverted pendulum).  
**Goals:** derive state-space model, linearize, design PID and LQR controllers, implement Kalman filter for IMU fusion, simulate and prepare embedded code.

**Requirements**
- Linear algebra, ODEs
- State-space modeling
- PID, LQR, Kalman filter basics

**Tools**
- MATLAB / Simulink (recommended)
- Python (NumPy, SciPy, Matplotlib, control)
- Optional hardware: Raspberry Pi Pico, MPU6050, motor driver (BTS7960)

**Folder structure**
- `src/` — control code and scripts
- `sim/` — simulation models
- `docs/` — derivation and notes
- `images/` — figures

**How to run (example)**
1. Open `sim/self_balance_model.slx` in Simulink OR run `python sim/run_simulation.py`.
2. Tune controllers in `src/` and plot results in `images/`.
