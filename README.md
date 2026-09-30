# Falling Leaves Simulation

[English](README.md) | [日本語](README.ja.md)

A browser-based falling-leaf simulation in HTML, CSS, and JavaScript, with adjustable wind and leaf count, pause controls, and a simplified drag-and-lift model.

## Use

Open `index.html` in a browser, then adjust wind strength and leaf count from the controls. Pause the simulation or add more leaves as needed. A static file server can also serve the project.

![Simulation](assets/simulation-screenshot.png)

Each leaf tracks position, velocity, angle, angular velocity, mass, area, drag, and lift. Each frame computes the wind and relative air velocity, applies drag, lift, and gravity, and updates motion and rotation. This is a simplified visual model rather than a scientific fluid simulation.


## Contents

- [assets/](assets)

## Detailed documentation

The [Japanese guide](README.ja.md) retains the complete original setup instructions, configuration, examples, project status, and limitations. Supporting documents keep their existing language.
