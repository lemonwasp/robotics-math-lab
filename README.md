# Robotics Math Lab

**A study roadmap and learning journal for mathematics, physics, robotics, and AI.**

[한국어 README](README.ko.md) · [9-month curriculum](docs/roadmap.md) · [Study method](docs/study-method.md) · [Open learning tasks](tasks/README.md)

## Purpose

This repository is a place to **learn, reason, and apply knowledge independently**. It connects mathematical and physical foundations to robotics, sensor systems, and AI, with an eye toward future robotics graduate study and physical-AI engineering.

This is a **curriculum and task scaffold**, not a collection of pre-solved assignments. Code, solutions, graphs, and test results will be added **only after the learner has studied, attempted, and verified them**.

## Study process

1. Ask *why* a concept works, starting from definitions and intuition.
2. Solve a carefully chosen problem independently, on paper or in notes.
3. Check assumptions, dimensions, counterexamples, and mistakes.
4. Explore how the concept might be applied to a robot, a sensor, or AI.
5. Implement and test **later**, when ready; document actual evidence.
6. Reflect on what was learned and what remains unclear.

Hints can be requested before a complete solution. Avoid automatically generated solutions to unattempted tasks.

## Topic map

| Area | Topics | Intended application |
| --- | --- | --- |
| [Calculus](math/calculus/README.md) | Geometry, trigonometry, derivatives, integrals, multivariable calculus | Motion, sensitivity, optimization |
| [Linear algebra](math/linear_algebra/README.md) | Vectors, matrices, transformations, eigenvalues | Robot coordinates, representation learning |
| [Differential equations](math/differential_equations/README.md) | ODEs, numerical methods, stability | Physical dynamics and control |
| [Probability](math/probability/README.md) | Bayes, distributions, estimation | Uncertain sensors and ML |
| [Mechanics](physics/mechanics/README.md) | Motion, forces, torque, energy, rotation | Robot motion and dynamics |
| [Electromagnetism](physics/electromagnetism/README.md) | Fields, circuits, induction, EM waves | Motors, radar, sensors |
| [Waves and signals](physics/waves_signals/README.md) | Oscillation, Fourier, sampling, filtering | mmWave data and edge AI |
| [Robotics](robotics/kinematics/README.md) | Kinematics, dynamics, control, state estimation | Robot arm and physical-AI tasks |
| [AI](ai/README.md) | Gradients, neural networks, signal processing | Learning and sensor interpretation |

## Initial task queue (unsolved)

1. [Geometry, unit circle, and trigonometry](tasks/01_geometry_and_trigonometry.md)
2. [Parametric motion and derivatives](tasks/02_parametric_motion.md)
3. [2-link robot-arm exploration](tasks/03_two_link_arm.md)

Each task describes **questions, prerequisites, and expected learning evidence**, without answers or finished implementation. The order can change as understanding develops.

## Roadmap and evidence

- [November 2026 – July 2027 study plan](docs/roadmap.md)
- [Feynman-style study and reflection protocol](docs/study-method.md)
- [University admission / challenging-problem tracker](admissions/README.md)
- [Future experiment organization](experiments/README.md)

| Item | Status |
| --- | --- |
| Curriculum outline | Drafted |
| Topic and task index | Drafted |
| Independently solved assignments | Not recorded yet |
| Implemented robotics / AI experiments | Not started |
| Tests and empirical results | Not started |

## Related work

- [IBUKI (JPHACKS hs_2605)](https://github.com/jphacks/hs_2605) motivates future study of signal processing, electromagnetic waves, sensor uncertainty, and edge AI. This repository makes no claim to reproduce or extend that project's measurements.

## Rules

- Do not post solutions before attempting and understanding the problem.
- Distinguish **planned**, **in progress**, and **verified by the learner**.
- Attribute problem sources without redistributing unauthorized exam scans.
- Document real evidence only: reasoning, tests, plots, mistakes, and limitations.
- Avoid uploading private data, proprietary code, or secrets.
