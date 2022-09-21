# Nonlinear-Control-Systems
Projects implemented for the needs of Nonlinear Control Systems course

This project is divided in two parts.

## Part 1
Given the system:

$$ M\ddot{x} + F_b(\dot{x}) + kx = 0 $$

where:

$$ \begin{alignat*}{3}
& F_b(\dot{x}) && = ((\dot{x}-b) - c)^2 + d, && \quad \text{for} \quad \dot{x} \geq b \\
&  && = -((\dot{x}-b) + c)^2 - d, && \quad \text{otherwise}
\end{alignat*} $$

Find the equilibrium point and characterize its stability for the cases where the velocity b takes increasing values b = 1, b = 2 and b = 2.1 by reviewing the phase portrait of the system. In addition, plot the spectral portrait for various initial values and selectively some of the time responses of the state variables. Parameters M, k, c, d are given.

## Part 2
Given the system:

$$ \begin{gather*} 
D\ddot{q} + C(q, \dot{q})\dot{q} + G(q) = K(\theta - q) \\
J\ddot{\theta} + B\dot{\theta} + K(\theta - q) = u 
\end{gather*} $$

