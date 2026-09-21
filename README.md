# Nash-Moser Solver
Implementation of the Nash-Moser algorithm to solve Partial Differential Operators with infinitesimally invertible linearization.

The project aims to provide a usable algorithm that takes a partial differential operator in entry, computs it's linearizaiont

# Objectives
## 1st Objective
Given a Partial Differentail operator 

$$
D : C^\infty(\mathbb{R}^n, \mathbb{R}^m) \longrightarrow C^\infty(\mathbb{R}^n, \mathbb{R}^k)
$$

And

$$
f \in C^\infty(\mathbb{R}^n, \mathbb{R}^m)
$$

We want to:

- Compute the linearization
$$
L_f
$$
of $D$ at $f$.
- Check if $L_f$ is right invertible and compute its right inverse
$$
M_f
$$
- Use the Nash-Moser algorithm to deduce a numerical solution to the equation
$$
D(f) = 0
$$

