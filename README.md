# Gauss VR

An interactive VR simulation of Gauss's Law for introductory electromagnetism, built with Three.js and WebXR for Meta Quest.

Designed and developed by Anthony Danese, high school physics teacher.

## What It Does

Students can explore Gauss's Law in an immersive 3D environment by placing positive and negative point charges inside a transparent Gaussian surface and observing how the electric field vectors on the surface respond in real time. The simulation demonstrates that the total electric flux through a closed surface depends only on the enclosed charge, regardless of where inside the surface the charge is placed.

## Features

- Transparent cubic Gaussian surface with electric field vectors on each face
- Superposition of multiple charges, up to 2 positive and 2 negative
- Grab, move, snap, and throw charges in 3D space
- Grip-based spin control for a full 360 degree view
- Live flux readout based on enclosed charge
- In-VR help and recenter controls

## Controls

| Action | Control |
|---|---|
| Spawn positive charge | A button on the right controller |
| Spawn negative charge | B button on the right controller |
| Grab charge | Trigger near a charge |
| Move charge | Hold trigger and move controller |
| Throw charge | Fling and release trigger |
| Change charge magnitude | Swipe up or down through a nearby charge |
| Spin scene | Grip button and move controller |
| Reset position | Both grip buttons together |
| Walk / strafe | Left thumbstick |
| Snap turn | Right thumbstick left or right |

## How To Use

1. Open your Meta Quest browser and navigate to the live sim.
2. Select `Enter VR`.
3. Use the A and B buttons to spawn charges.
4. Move charges inside, on, and outside the cube to compare how the flux readout changes.

Live sim: https://phys-viz.github.io/GaussVR/

## Pedagogical Context

This simulation is designed as a conceptual companion to a quantitative Gauss's Law lab. Students use this VR experience to build spatial intuition before working with numerical flux calculations. It is part of a broader suite of VR simulations for introductory electromagnetism.

## Tech Stack

- [Three.js](https://threejs.org/) r128
- WebXR API
- Vanilla JavaScript with no build tools or frameworks
- Hosted on GitHub Pages

## License

Copyright 2025 Anthony Danese. Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Free for educational use. Commercial use requires explicit written permission.
