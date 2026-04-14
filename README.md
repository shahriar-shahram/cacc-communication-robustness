## System Architecture

### Cooperative Driving Topology (CACC)

<p align="center">
  <img src="assets/diagrams/cacc_topology.png" width="600">
</p>

- Vehicles receive information from multiple predecessors (APLF topology)
- Combines:
  - Local sensing (radar)
  - V2V communication
- Enables faster disturbance propagation and improved stability

---

### Vehicle Model (Bicycle Model)

<p align="center">
  <img src="assets/diagrams/bicycle_model.png" width="600">
</p>

- Simplified dynamic model for control design
- States include:
  - Position, velocity, heading
- Inputs:
  - Acceleration
  - Steering angle
- Used for MPC prediction over finite horizon
