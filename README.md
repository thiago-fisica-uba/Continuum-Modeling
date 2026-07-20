# Introducción al Modelado Continuo (IMC)

Personal work from the course *Introducción al Modelado Continuo*
(Introduction to Continuum Modeling), Facultad de Ciencias Exactas
y Naturales, Universidad de Buenos Aires (FCEN–UBA), first semester
of 2026, taught by Prof. Julián Fernández Bonder (Instituto de Cálculo,
FCEN–CONICET; Departamento de Matemática, FCEN–UBA).

## About the course

The course introduces continuum modeling as a framework for formulating
explicit hypotheses about the mechanisms governing a system, analyzing
the qualitative structure of its solutions, and studying long-term
behavior. It emphasizes the interplay between mathematical formulation,
numerical simulation, and data analysis, with roughly half of the
course devoted to computational lab work.

The material is organized into three parts.

**Part I — Nonlinear dynamics.** ODE-based models (population dynamics,
Lotka–Volterra, logistic growth, SIR); mechanical systems; flows and
phase diagrams; the Hartman–Grobman theorem; conservative systems and
Lyapunov functions; the Poincaré–Bendixson theorem; structural stability
and bifurcations, including the Hopf bifurcation.

**Part II — Fourier analysis.** Fourier series (real and complex forms);
Bessel's inequality and Parseval's identity; pointwise, uniform, and
mean-square convergence; the Gibbs phenomenon; the continuous Fourier
transform and inversion formula; the discrete Fourier transform and
the Fast Fourier Transform (FFT). Applications to signal denoising
and image compression.

**Part III — Partial differential equations.** The diffusion/heat
equation, derived from conservation laws and from the random-walk
picture; the Laplace / Poisson equation; the wave equation. Solution
methods based on Fourier series, the fundamental solution, and
d'Alembert's formula.

## Contents of this repository

- `notes/` — reference course notes (see *Attribution* below).
- `labs/` — computational lab work: numerical integration of dynamical
  systems, phase-portrait exploration, FFT experiments, and PDE solvers.
- `exercises/` — worked solutions to theoretical exercises.

## Attribution

The reference notes included in this repository were written by
Prof. Julián Fernández Bonder and are hosted here for personal
study purposes; all rights belong to the author. Any original work
in this repository — labs, exercises, and additional summaries —
is my own.
