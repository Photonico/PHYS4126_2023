# Quiz 4

## 1

Bragg's Law

$$n \lambda = 2 d \sin (\theta)$$

where:

$d$ is interplanar spacing, $n$ is order of the diffraction peak, $\theta$ is angle of diffraction.

$$d = \frac{n\lambda}{2 sin{(\theta)}}$$

for $2\theta=42.3 degree$: $d1 \approx 1.203 \rm\r{A}$;

for $2\theta=49.2 degree$: $d2 \approx 1.070 \rm\r{A}$;

for $2\theta 72.2 degree$: $d3 \approx 0.851 \rm\r{A}$;

for $2\theta=87.4 degree$: $d4 \approx 0.811 \rm\r{A}$.

The ratios between these d-spacings: $d1:d2:d3:d4 \approx 2.245:1.946:1.375:1.172 \approx 1:0.867:0.612:0.522$

These ratios suggest that it might be a BCC lattice. Then, we have:

$$ \frac{d1}{(a/\sqrt{2})}\approx\frac{d1}{(a/\sqrt{4})}\approx\frac{d1}{(a/\sqrt{6})}\approx\frac{d1}{(a/\sqrt{8})} $$

The lattice constant is $a \approx 3.178 \rm\r{A}$

## 3

In terms of wave vector $k$ and group velocity $v_g(k)$ can express the momentum $p=\hbar k$

The group velocity is thederivative of the energy $E$ with respect to the wave vector $k$:

$$ v_g(k) = \frac{\partial E}{\partial k} $$

where $E=\hbar\omega(k)$.

Applied the Newton's law:

$$ F=\frac{{\rm d}p}{{\rm d}t} = m \frac{{\rm d}v}{{\rm d}t}$$

and ${\rm d}p = \hbar{\rm d}k$

We have:

$$ m^*\frac{{\rm d}}{{\rm d}t}\left(\frac{\partial E}{\partial k}\right) = \hbar\frac{{\rm d}k}{{\rm d}t}$$

We arrive the expression for the effective mass:

$$ m^* = \hbar^2\left(\frac{\partial^2E}{\partial k^2}\right)^{-1} $$

$\rm{Q.E.D}$

## 4

### (a)

In a 2-dimensional square lattice, the first Brillouin zone is also a square. The corner points of the first Brillouin zone are at wave vectors $(k_x, k_y) = (\pm\pi/a, \pm\pi/a)$, while the midpoints of the side faces are at $(k_x, k_y) = (0, \pm\pi/a)$ or $(\pm\pi/a, 0)$, where $a$ is the lattice constant.

For a free electron in a 2-dimensional lattice, the dispersion relation is

$$ E(kx, ky) = \frac{\hbar^2(k_x^2 + k_y^2)}{2m} $$

The kinetic energy of a free electron at a corner of the first Brillouin zone:

$$E_{corner} = \frac{\hbar^2((\pi/a)^2+(\pi/a)^2)}{2m}=\frac{\hbar^2(2\pi^2/a^2)}{2m}$$

Next, calculate the kinetic energy of a free electron at the midpoint of a side face of the zone:

$$E_{midpoint} = \frac{\hbar^2(\pi/a)^2}{2m} $$

Then, we arrive the factor $b$:

$$ b = \frac{E_{corner}}{E_{midpoint}} = \frac{2\pi^2}{\pi^2} = 2 $$

### (b)

Fot the 3-dimensional simple cubic lattice, the first Brillouin zone is also a cube. The corner points of the first Brillouin zone are at wave vectors $(k_x, k_y, k_z) = (\pm\pi/a, \pm\pi/a, \pm\pi/a)$, while the midpoints of the side faces are at $(k_x,k_y,k_z)=(\pm\pi/a,0,0)$,$(0,\pm\pi/a,0)$, or $(0,0,\pm\pi/a)$.

For a free electron in a three-dimensional lattice, the dispersion relation is given by the equation:

$$ E(k_x, k_y, k_z) = \frac{\hbar^2(k_x^2+k_y^2+k_z^2)}{2m} $$

The kinetic energy of a free electron at a corner of the first Brillouin zone:

$$E_{corner} = \frac{\hbar^2((\pi/a)^2+(\pi/a)^2+(\pi/a)^2)}{2m}=\frac{\hbar^2(3\pi^2/a^2)}{2m}$$

Next, calculate the kinetic energy of a free electron at the midpoint of a side face of the zone:

$$E_{midpoint} = \frac{\hbar^2(\pi/a)^2}{2m} $$

Then, we arrive the factor $b$:

$$ b = \frac{E_{corner}}{E_{midpoint}} = \frac{3\pi^2}{\pi^2} = 3 $$

### (c)

In a 2D or 3D crystal of a divalent element, the solid can be a metal if the energy bands are partially filled, allowing for free movement of electrons and electrical conduction.

This is possible in the nearly-free electron model, where electrons are weakly bound by a periodic potential.

For a divalent element, there are two valence electrons per unit cell, which can lead to partially filled bands in certain lattice structures.

A partially filled band allows electrons to move freely, making the solid a metal.
