# SpaceTimeFEM_2023-2024
Exercises for the course "Space-time methods" at the Leibniz University Hannover in the winter semester 2023/2024

## Exercise 1
Introduction to:
- Python
- SymPy
- FEniCS
- git

**Homework for Exercise 1:**

Solve heat equation with space-time FEM in FEniCS.

$$
\partial_t u - \partial_{xx} u = f
$$

## Exercise 2
Solve ODE 

$$
\begin{align}
\partial_t u &= \lambda u, \\
u(0) &= u_0,
\end{align}
$$

using SymPy and NumPy.

**Homework for Exercise 2:** 

Use same methodology for

$$
\begin{align}
\partial_t v &= -u, \\
\partial_t u &= v, \\
u(0) &= 1, \\
v(0) &= 0.
\end{align}
$$

## Exercise 3
Solve heat equation (from the Homework to Exercise 1) with tensor-product space-time FEM.
Implementation in FEniCS.

**Homework for Exercise 3:** 

Try to find ways to speed up the code from Exercise 3.

## Exercise 4

Solve the nonlinear heat equation

$$
\partial_t u - \partial_{xx} u + u^2 = f
$$

with tensor-product space-time FEM in FEniCS. 
Time integration is performed with SymPy and the spatial FEM (incl. automatic differentiation) is done in FEniCS.

Presentation of topics for group projects
