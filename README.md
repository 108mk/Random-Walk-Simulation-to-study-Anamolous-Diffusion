# Installation
## Requirements: 

    The only requirement is Python 3.8 or above
    All used libraries are within Python standard module
    You don't need to install any extra module

# Project details:
### $\spadesuit$ To study a $time\ dependent\ viscoelastic\ fluid$ that can be modelled by Maxwell-Voigt type description.
![alt text](https://github.com/108mk/Random-Walk-Simulation-to-study-Anamolous-Diffusion/blob/f71bfa1af2486db9b9027e288b7d79fdd03e4011/demo%20images/maxwell%20voigt%20material.png?raw=true)
### $\spadesuit$ We simulated [Langevin equation](https://en.wikipedia.org/wiki/Langevin_equation#Harmonic_oscillator_in_a_fluid) (a Stochastic differential equation ) for this viscoelastic system-
# $m\cdot \ddot x = -\eta(t)\cdot \dot x -\kappa(t)\cdot x + \delta(t)$ ;
> where, $\delta(t)$ is Gaussian noise term
### $\spadesuit$ System under study:
> Take elasticity of the system: $\kappa (t),\ and$  viscosity of the system $\eta (t)$, defining the characteristic parameter of the system $\tau (t) \equiv \lambda (t) = \frac{\eta (t)}{\kappa (t)}$
### $\star$ Material-1: Exponential ageing $\rightarrow  \lambda (t) = \exp (t/t_0)$ 
### $\star$ Material-2: Power law ageing $\rightarrow \lambda (t) =  (t/t_0)^m $
### $\star$ The phenomena of 'ageing' is studied in microrheology via the Brownian motion of tracer bead particles. Hence, we appropriately modelled the materials and simulated the tracer bead trajectory for relevant insight.
![alt text](https://github.com/108mk/Random-Walk-Simulation-to-study-Anamolous-Diffusion/blob/f71bfa1af2486db9b9027e288b7d79fdd03e4011/demo%20images/trajectories.png?raw=true)
![alt text](https://github.com/108mk/Random-Walk-Simulation-to-study-Anamolous-Diffusion/blob/f71bfa1af2486db9b9027e288b7d79fdd03e4011/demo%20images/ett-1.png?raw=true)
![alt text](https://github.com/108mk/Random-Walk-Simulation-to-study-Anamolous-Diffusion/blob/f71bfa1af2486db9b9027e288b7d79fdd03e4011/demo%20images/ett-2.png?raw=true)
## $\left< R^2 \right>\ \rightarrow\ mean\ sqaured\ displacement\ and,\ \ t, \xi \rightarrow\ simulation\ time$
## 🌱 $My\ first\ humble\ contribution\ to\ Open-Source!!!$ 🌱
