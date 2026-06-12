Circular Restricted Three-Body Problem

Numerical simulation of the circular restricted three-body problem with the Earth, the Moon and a spacecraft. The coordinate frame is Earth‑centered inertial. Earth and Moon are modeled as point masses. The Moon's orbit around Earth is a circular orbit. The mass of the spacecraft is insignificance with respect to the Earth and Moon. The equation of motion equates the spacecraft's acceleration with the accelerations imparted by the gravity of the Earth and the gravity of the Moon (no Sun, no J₂ coefficient that quantifies Earth’s equatorial bulge and its effect on spacecraft orbits). Units are km, km/s, seconds. Required libraries are NumPy, SciPy, and Matplotlib. The integrator of the equation of motion is the scipy solver solve_ivp. The output includes plots, analysis, and an animation.

The Artemis 2 Lunar flyby mission with its free-return trajectory was the inspiration. This simulation, however, does not match a particular mission. THe positions of the Earth, Moon, and spacecraft are not based on ephimerides. This simulation is a first-order approximation. If Artemis missions will continue going to the Moon and back, it is relevant to model and study the 3-body problem. This simulation is a first step. 

[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](LICENSE)
![Language](https://img.shields.io/badge/Language-Python-blue.svg)
![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)


