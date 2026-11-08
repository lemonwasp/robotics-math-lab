# 9-month curriculum: November 2026 – July 2027

This is a **proposed personal study sequence** for strengthening applied mathematics, physics, robotics and AI fundamentals. Time allocations are flexible. All experiments and tests below are **future targets, not completed work**.

The study loop is: concept → independent reasoning and problem attempt → physics/robotics/AI connection → optional implementation and tests **when ready** → reflection. Problem sources may include strong historical or modern mathematics and physics problem collections from Japan, Korea, the US and Europe.

| Month | Core mathematics | Physics and engineering | Build / proof of learning |
| --- | --- | --- | --- |
| **1 · Nov 2026** | Circle and coordinates; trigonometry; functions, limits, derivatives; parametric curves; chain rule; integrals | Position, velocity, acceleration; vectors and planar motion | Questions about a 2-link arm; independent geometry and motion reasoning |
| **2 · Dec** | Multivariable derivatives; gradients; total derivatives; Jacobians; vectors; matrix operations; determinants | Newton's laws; force/torque; work/energy; rotational motion | Inverse kinematics, singularities and vector transformation experiments |
| **3 · Jan 2027** | Linear independence; bases; rank; eigenvalues/eigenvectors; diagonalization; symmetric matrices; SVD basics | Rigid-body motion; momentum, inertia, conservation laws | Coordinate frame transformations; simple robot dynamics |
| **4 · Feb** | First/second-order ODEs; initial conditions; coupled ODEs; linear systems; stability; introduction to PDEs | Harmonic oscillator, damping, resonance; RLC analogies | Numerically integrate a pendulum or mass-spring system; compare with analytic limits |
| **5 · Mar** | Complex numbers; Euler's formula; Fourier series/transform; convolution; sampling; Laplace transform | Waves, phase, interference; electromagnetic fields and induction | Synthetic radar/sinusoid filtering; spectra, aliasing, denoising |
| **6 · Apr** | Probability distributions; conditional probability; expectation/covariance; Bayes; least squares | Sensor noise; measurement models; circuits and sensor interfaces | Kalman filter and noisy motion-state estimation, with error metrics |
| **7 · May** | Optimization; partial derivatives; gradients; chain rule; constrained optimization; numerical methods | Feedback; transfer functions; state-space models; controllability | PID trajectory tracking; gradient descent from scratch, with plots |
| **8 · Jun** | Numerical linear algebra; matrices in ML; statistics, hypothesis tests; introductory deep learning math | Motors, actuation, sensing, computational limits | Small neural network / radar time-series experiment; clear train/eval split |
| **9 · Jul** | Mixed proofs, advanced problems, weak-topic repairs; timed practice sessions | Integrated mechanical/electrical/control questions | End-to-end 2-link robot demo + review document; oral 3-minute derivations |

## Detailed skill ladder

### Mathematics

1. **Geometry and trigonometry:** Cartesian/polar coordinates; equation of a circle; line-circle intersections and tangents; unit circle; radian measure; sine/cosine; identities; parametric ellipse/hyperbola.
2. **Single-variable calculus:** limit and continuity; derivative as local linear approximation; product/quotient/chain rules; implicit and parametric differentiation; second derivative; optimization; definite integral, substitution, integration by parts, fundamental theorem.
3. **Multivariable calculus:** partial derivative; gradient/directional derivative; total differential; Jacobian; Hessian; Taylor approximation; double integrals; constrained extrema and Lagrange multipliers.
4. **Linear algebra:** vectors; dot/cross products; projections; bases; matrices and inverses; determinant; rank/null space; eigenvalues/eigenvectors; orthogonality; least squares; SVD.
5. **Differential equations:** separable/linear ODEs; constant-coefficient second-order ODEs; coupled state equations; Euler and Runge–Kutta methods; equilibria and stability; introductory PDE concepts.
6. **Signals and transforms:** complex exponentials; Euler's formula; Fourier series and transform; DFT/FFT; convolution; sampling/aliasing; filters; Laplace transform and poles.
7. **Probability, statistics and AI:** conditional probability, Bayes' rule, Gaussian noise, variance/covariance, estimation, regression, gradient-based optimization, backpropagation and evaluation.

### Physics

1. **Mechanics:** SI units and dimensional analysis; position/velocity/acceleration; Newton's laws; free-body diagrams; friction; energy/momentum; circular motion; torque; angular momentum; inertia; oscillations.
2. **Waves and electromagnetism:** oscillation, phase, superposition, interference, fields, electrostatic potential, magnetic fields, induction, Maxwell-equation intuition, electromagnetic wave propagation and radar sensing.
3. **Circuits / sensors:** voltage-current-resistance, Kirchhoff rules, RC/RL/RLC response, ADC sampling, motor actuation, noise and real-time measurement limits.
4. **Control and robotics physics:** rigid-body frames, kinematics/dynamics, state-space representation, damping/stability, feedback, PID, model error and state estimation.

### Programming and problem-solving practice

- Python standard library + NumPy/Matplotlib when the experiment calls for them; unit tests, simulation, numerical comparisons and reports.
- Progress into C/C++ fundamentals when robotics, embedded systems, or numerical experiments call for them.
- Use original problems and properly attributed, legally accessible archival problems from Japan, South Korea, the US and Europe. Favor problems that require connections or insight over recency alone.
- Maintain a separate [advanced problem-solving tracker](../problem-solving/README.md) with sources, independent attempts and reflections.

## Acceptance evidence by milestone

- **M1:** tested kinematics + Jacobian with derivation and graph.
- **M2–M3:** analytical IK and dynamics checks, with singularity/energy cases.
- **M4–M5:** time-domain model matches qualitative and quantitative physics; signal processing tests on synthetic data.
- **M6–M7:** state-estimation/control benchmark includes baselines, metrics, plotted errors.
- **M8–M9:** integrated demonstration, oral explanation, solved problems and documented limitations.

No milestone is complete solely because a lecture was watched or copied code ran.
