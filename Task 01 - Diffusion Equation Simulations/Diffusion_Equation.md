# Numerical Analysis of Diffusion Equation

## Mean Field Dynamos

The mean-field dynamo equation describes the generation of a magnetic field in a turbulent conducting fluid. The general form of the mean-field dynamo equation, neglecting the alpha effect, velocity terms, and assuming the diffusion coefficient is scalar, along with the condition that the divergence of the magnetic field ($\nabla \cdot \mathbf{B} = 0$), is given by:

$$
\frac{\partial \bar{\mathbf{B}}}{\partial t} = \nabla \times (\bar{\mathbf{v}} \times \bar{\mathbf{B}}) + \eta \nabla^2 \bar{\mathbf{B}}
$$

Where:
- $\bar{\mathbf{B}}$ is the magnetic field vector.
- $ \bar{\mathbf{v}} $ is the velocity vector of the conducting fluid.
- $ \eta $ is the magnetic diffusion coefficient.
- $ \nabla \times (\bar{\mathbf{v}} \times \bar{\mathbf{B}}) $ represents the stretching and folding of the magnetic field lines due to the fluid motion.
- $ \eta \nabla^2 \bar{\mathbf{B}} $ represents the diffusion of the magnetic field.

Neglecting the alpha effect and the stretching term ($ \bar{\mathbf{v}} \times \bar{\mathbf{B}} $) and considering a scalar diffusion coefficient with $ \nabla \cdot \mathbf{B} = 0 $, the simplified mean-field dynamo equation becomes:

$$
\frac{\partial \bar{\mathbf{B}}}{\partial t} = \eta \nabla^2 \bar{\mathbf{B}}
$$

This equation describes the evolution of the magnetic field solely due to diffusion, without any contribution from fluid motion or turbulent effects.

For the radial component ( $B_r$ ):
$$
\frac{\partial \bar{B}_r}{\partial t} = \eta \left( \frac{1}{r} \frac{\partial}{\partial r} \left( r \frac{\partial \bar{B}_r}{\partial r} \right) - \frac{Br}{r^2}+ \frac{\partial^2 \bar{B}_r}{\partial z^2} \right)
$$

For the azimuthal component ($ B_{\phi}$ ):
$$
\frac{\partial \bar{B}_\phi}{\partial t} = \eta \left( \frac{1}{r} \frac{\partial}{\partial r} \left( r \frac{\partial \bar{B}_\phi}{\partial r} \right) - \frac{B_{\phi}}{r^2} + \frac{\partial^2 \bar{B}_\phi}{\partial z^2} \right)
$$

For the axial component ($ B_z $):
$$
\frac{\partial \bar{B}_z}{\partial t} = \eta \left( \frac{1}{r} \frac{\partial}{\partial r} \left( r \frac{\partial \bar{B}_z}{\partial r} \right) - \frac{B_z}{r^2} + \frac{\partial^2 \bar{B}_z}{\partial z^2} \right)
$$

These spiral galxies can be approximated as a spatially symmetric thin disc where $ \frac{\partial}{\partial \phi} = 0 $. Also, observe $B_z$  is much weaker than  $ B_r $ and $ B_\phi $, we can neglect $ B_z $ in equations for $ B_r $ and $ B_\phi $. Thus, we focus on solving Eq. (11.2a) and (11.2b). Alternatively, \( B_z \) can be determined from the solenoidality condition $ \nabla \cdot \mathbf{B} = 0 $ as soon as $ B_r $ and $ B_{\phi} $ have been solved for.