# Condensed Matter Physics Assignment

Lu Niu

## 1

### (a)

In the orthorhombic crystal, the primitive lattice vectors of the direct and reciprocal lattices can be written as follows:

The direct primitive lattice vectors are:
$$ a_1 = 2i $$
$$ a_2 = 3j $$
$$ a_3 = 5k $$

Where $i$, $j$, $k$ are unit vectors along the $x$, $y$, $z$ directions respectively.

The reciprocal lattice vectors can be calculated using the following formula:

$$b_1 = 2\pi(a_2 \times a_3) / (a_1\cdot(a_2 \times a_3))$$
$$b_2 = 2\pi(a_3 \times a_1) / (a_1\cdot(a_2 \times a_3))$$
$$b_3 = 2\pi(a_1 \times a_2) / (a_1\cdot(a_2 \times a_3))$$

In this case, as the direct primitive lattice vectors are along the coordinate axes, the reciprocal lattice vectors can be simplified as:

$$b_1 = 2\pi/a_1 $$
$$b_2 = 2\pi/a_2 $$
$$b_3 = 2\pi/a_3 $$

It is worth noting that the units of the reciprocal lattice vectors are 1/Angstrom, which is different from the Angstrom units of the direct lattice.

### (b)

The wavevector $k$ at the first Brillouin zone boundary corresponds to the reciprocal lattice vectors.

In an orthorhombic crystal with lattice parameters $a$, $b$, $c$:

For the $[010]$ direction, the corresponding reciprocal vector will have a magnitude of $\pi/b$. Therefore, the wavevector at the boundary in this direction will be $k = \pi/b$ (in units of inverse Angstroms).

Similarly, for the $[110]$ direction, the magnitude of the corresponding reciprocal vector will be $\pi/\sqrt(a^2+b^2)$, so the wavevector will be $k = \pi/\sqrt(a^2+b^2)$.

For the $[111]$ direction, the reciprocal vector will have a magnitude of $\pi/\sqrt(a^2+b^2+c^2)$, thus the wavevector will be $k = \pi/\sqrt(a^2+b^2+c^2)$.

### (c)

metal

### (d)

We have:
$$ E_c = 0.7\left[\frac{1}{5} - \frac{1}{2}sin^2\left(\frac{k_x a}{2}\right) \right] $$
$$ E_v = 0.6[cos(k_x a)-1] $$

For an orthorhombic crystal, the group velocity of electrons in the conduction band can be calculated by taking the derivative of the energy E with respect to the wavevector k:

$$ v_g = \frac{1}{\hbar}\frac{{\mathrm d}E}{{\mathrm d}k} $$

In the given E_c, we can take the derivative with respect to $k_x$. Considering the known lattice constant a, we obtain:

$$ \frac{{\mathrm d}E_c}{{\mathrm d}k_x} = -0.7a\sin(k_xa)\cos(k_xa) $$

At $k_x = 0$, the group velocity $v_g = 0$ (since both sin and cos are 0 at this point).

At $k_x = pi/(2a)$, inserting into the above expression, as $\cos(\pi/2) = 0$ and $\sin(\pi/2) = 1$, we get:

$\frac{{\mathrm d}E_c}{{\mathrm d}k_x} = 0$

Thus, the group velocity of electrons in the conduction band is 0 at both $k_x = 0$ and $k_x = \pi/(2a)$.

## 2

### (a)

The basis for the perovskite structure of strontium titanate (SrTiO3) consists of four atoms: one Sr atom, one Ti atom, and three O atoms.

In terms of lattice coordinates, we could represent the positions as follows:

Sr is at the corner of the cube, its position can be given as $(0, 0, 0)$.
Ti is at the center of the cube, its position can be given as $(1/2, 1/2, 1/2)$.
O atoms are in the center of each face of the cube, their positions can be given as $(1/2, 1/2, 0)$, $(1/2, 0, 1/2)$, and $(0, 1/2, 1/2)$.

### (b)

The X-ray structure factor (F) can be calculated from the following formula:

$$ F = \sum f_j\exp(2\pi i(hu_j + kv_j + lw_j)) $$

The atomic form factors can be approximated as being proportional to the number of electrons in each atom (Z): $f(\mathrm{Sr}) ~ 38$, $f(\mathrm{Ti}) ~ 22$, and $f(\mathrm{O}) ~ 8$.

### (c)

### (d)

The Bragg's Law is used to calculate the diffraction angles in X-ray crystallography. It states that:

$$ n\lambda = 2d * \sin(\theta) $$

where: $d = a / \sqrt(h^2 + k^2 + l^2)$

Then, we can infer:

$$ 2\theta = 2\arcsin(n\lambda/(2a)\sqrt(h^2 + k^2 + l^2)) $$

In this case, $n = 1$ and $\lambda = 1.55 \rm\r{A}$.

Now let's calculate $2\theta$ for the $(100)$, $(110)$ and $(200)$ planes.

For $(hkl) = (100)$, we have $h = 1$, $k = 0$, $l = 0$:

$$ 2\theta = 2\arcsin((1.55)/(2 * 3.905)\sqrt(1^2 + 0^2 + 0^2)) $$

$$ 2\theta\approx 2\arcsin(0.198) \approx 211.37\frac{\pi}{180} \approx 22.74\frac{\pi}{180} $$

For $(hkl) = (110)$, we have $h = 1$, $k = 1$, $l = 0$:

$$ 2\theta = 2\arcsin((1.55)/(2 * 3.905)*\sqrt(1^2 + 1^2 + 0^2)) $$
$$ 2\theta\approx2\arcsin(0.198\sqrt2)\approx 2\approx16.26\frac{\pi}{180}\approx32.52\frac{\pi}{180} $$

For $(hkl) = (200)$, we have $h = 2$, $k = 0$, $l = 0$.
$$ 2\theta = 2\arcsin((1.55)/(2 *3.905)*\sqrt(2^2 + 0^2 + 0^2)) $$
$$ 2\theta\approx2\arcsin(0.198*\sqrt{4})\approx2*23.58\frac{\pi}{180}\approx47.16\frac{\pi}{180} $$

## 3

### (a)

In a diatomic linear chain with atoms of different masses arranged equidistantly, the phonon dispersion relation depicts the relationship between the energy and momentum of each vibrational mode (phonon). As this is a diatomic chain, two distinct phonon branches are observed: the acoustic branch and the optical branch.

In the acoustic branch, the energy (or frequency) increases linearly with momentum and then starts to curve near the first Brillouin zone boundary. In this vibrational mode, adjacent heavy and light atoms oscillate together in the same phase, meaning they oscillate in the same direction.

In the optical branch, there is a non-zero minimum energy when the momentum is zero, as the heavy and light atoms oscillate in opposite phases. The energy initially increases with momentum towards the first Brillouin zone boundary, and then decreases, forming a concave curve.

At the first Brillouin zone boundary, we typically observe two types of oscillations. For the acoustic branch, atoms oscillate out-of-phase, i.e., one up and the other down. For the optical branch, all atoms oscillate in-phase.

This is a concise description of the phonon dispersion relation in a diatomic linear chain, but the actual relation can be more complex depending on the specifics of the system.

### (b)

If the masses of the atoms in the diatomic chain are equal, it essentially becomes a monatomic chain. The phonon dispersion relation simplifies to a single branch. This acoustic branch shows a linear increase of energy with momentum, until it reaches the Brillouin zone boundary where the curve reflects back, implying that the atoms vibrate in phase. The optical branch disappears as there's no contrasting mass for out-of-phase vibrations.
