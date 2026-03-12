# Gauss VR

An interactive VR simulation of Gauss's Law for introductory electromagnetism, built with Three.js and WebXR for Meta Quest.

Designed and developed by Anthony Danese, high school physics teacher.

## What it does

Students can explore Gauss's Law in an immersive 3D environment — placing positive and negative point charges inside a transparent Gaussian surface and observing how the electric field vectors on the surface respond in real time. The simulation demonstrates that the total electric flux through a closed surface depends only on the enclosed charge, regardless of where inside the surface the charge is placed.

## Features

- Transparent cubic Gaussian surface with electric field vectors on each face
- Superposition of multiple charges (up to 2 positive, 2 negative)
- Grab and move charges freely in 3D space
- Spin the diorama with the grip button for a full 360° view
- Throw charges to remove them
- Analytical flux readout (coming soon)
- Multiple surface shapes: cube, sphere, cylinder (coming soon)

## Controls

| Action | Control |
|---|---|
| Spawn positive charge | A button (right controller) |
| Spawn negative charge | B button (right controller) |
| Grab charge | Trigger near charge |
| Move charge | Trigger + move controller |
| Throw charge | Trigger + fling + release |
| Spin scene | Grip button + move controller |
| Reset position | Both grip buttons simultaneously |
| Walk / strafe | Left thumbstick |
| Snap turn | Right thumbstick left/right |

## How to use

1. Open your Meta Quest browser and navigate to the live sim
2. Tap **Enter VR**
3. Use the A and B buttons to spawn charges
4. Grab and move charges to explore how the field vectors respond

**Live sim:** https://phys-viz.github.io/GaussVR/

## Pedagogical context

This simulation is designed as a conceptual companion to a quantitative Gauss's Law lab. Students use this VR experience to build spatial intuition before working with numerical flux calculations. It is part of a planned suite of VR simulations for introductory electromagnetism.

## Tech stack

- [Three.js](https://threejs.org/) r128
- WebXR API
- Vanilla JavaScript — no build tools, no frameworks
- Hosted on GitHub Pages

## License

© 2025 Anthony Danese. Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Free for educational use. Commercial use requires explicit written permission.
