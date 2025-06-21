# An Orbital Simulator

A simple 2D simulation of a satellite orbiting Earth using Newtonian mechanics.

## Features

### Satellite Trajectory Plot

Euler integration is used to simulate the satellite’s orbit based on chosen initial velocity and position. The resulting plot is then colored by speed.

### Tracking Energy

Plots of gravitational potential energy (GPE), kinetic energy (KE), and total mechanical energy throughout the orbit.

> Note: The total energy line is slightly curved. Ideally, it would be flat (energy conservation), but Euler’s method can over- or underestimate energy slightly due to breaking the orbit into many small linear steps and treating acceleration as constant in an outdated direction.

### Animation of Satellite Trajectory

Live animation of the satellite's motion around Earth, showing both position and trail.

## Usage

```bash
python orbital_simulator.py



