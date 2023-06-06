# Final Exam

Lu Niu

## 1

For the metal, the Fermi energy is a measure of the energy of the most energetic electrons in a metal at absolute zero temperature.

Fermi temperature is derived from the Fermi energy, with the relation $k_B T_F = E_F$. It provides a temperature scale for electron behavior.

Fermi surface is the surface in the reciprocal space which separates filled from unfilled electron states at the Fermi level at absolute zero temperature.

Where $k_B$ is Boltzmann's constant.

For Copper:

Atomic density of copper: $n_{\rm Copper} = 8.45 \times 10^{28} m^{-3}$

Due to Fermi energy:
$$ E_F = \frac{\hbar^2}{2m}(3\pi^2n_\text{Copper})^{2/3} $$

We have:
$$ E_F\approx 1.125 \times10^{-18} {\text J}$$

Fermi temperature have the following relation: $k_B T_F=E_F$.

We have:
$$T_F = \frac{E_F}{k_B} \approx 8.152 \times10^{4} {\rm K} $$

Fermi wavevector: $k_F = (3\pi^2n)^{1/3}$.

We have:
$$ k_F = (3\pi^2n_{\rm Copper})^{1/3} \approx 1.358\times10^{10} {\rm m}^{-1}$$.

## 2

Ionic Bonding: Transfer of electrons from one atom to another, creating positive and negative ions that attract each other. Example: Sodium chloride (NaCl).

Covalent Bonding: Atoms share pairs of electrons. Example: Water (H2O).

Metallic Bonding: Free electrons shared among a lattice of metal ions. Example: Copper (Cu).

Hydrogen Bonding: Special dipole-dipole interaction involving a hydrogen atom bonded to a highly electronegative atom. Example: Water (H2O).

Van der Waals Bonding: Weak forces due to transient polarization of electron clouds in atoms. Example: Helium (He) and Argon (Ar).

## 3

### (a)

The primitive vectors of a reciprocal lattice can be determined using the following formulas:

$$b_1= 2\pi\frac{a_2\times a_3}{a_1\cdot(a_2\times a_3)}$$
$$b_2= 2\pi\frac{a_3\times a_1}{a_1\cdot(a_2\times a_3)}$$
$$b_3= 2\pi\frac{a_1\times a_2}{a_1\cdot(a_2\times a_3)}$$

We have the real-space primitive vectors are:

$$a_1 = (a, 0, 0)$$
$$a_2 = (0, a, 0)$$
$$a_3 = (0, 0, c)$$

Then, we can infor:

$$b_1 = (0, 0, 2\pi/a)$$
$$b_2 = (0, 0, -2\pi/a)$$
$$b_3 = (0, 0, 2\pi/c)$$

Given that $a = 4.2 \rm\r{A}$, and $c = 6.3 \rm\r{A}$, we arrive:

$$b_1 = (0, 0, 0.5\rm\r{A})$$
$$b_2 = (0, 0, -0.5\rm\r{A})$$
$$b_3 = (0, 0, 0.32\rm\r{A})$$

### (b)

The angle of diffraction in X-ray crystallography can be calculated using Bragg's law:

$$ n\lambda = 2 d \sin(\theta) $$

Given that the crystal is $a$ body-centered tetragonal structure with lattice parameters a and $c$, the distances between diffracting planes $d$ for the first few peaks can be calculated as:

* For the $(1 1 0)$ plane, $d=\sqrt{a^2+a^2}=\sqrt{2}a$;

* For the $(2 0 0)$ plane, $d=a/2$;

* For the $(1 1 1)$ plane, $d=\sqrt{a^2+a^2+c}$.

Given that $a = 4.2 \rm\r{A}$, and $c = 6.3 \rm\r{A}$, we arrive:

$$d_{(1 1 0)} = 5.94 \rm\r{A}$$
$$d_{(2 0 0)} = 2.10 \rm\r{A}$$
$$d_{(1 1 1)} = 7.82 \rm\r{A}$$

Using Bragg's law, we arrive:

$$\theta_{(1 1 0)} = 0.251 \rm{rad}$$
$$\theta_{(2 0 0)} = 0.730 \rm{rad}$$
$$\theta_{(1 1 1)} = 0.192 \rm{rad}$$


## 4

* Point A: Velocity is negative (moving in the negative k direction), and the effective mass is negative.

* Point B: Velocity is negative, and the effective mass is positive.

* Point C: Velocity is positive (moving in the positive k direction), and the effective mass is positive.

* Point D: Velocity is positive, and the effective mass is negative.

The effective mass is likely largest near points B or C, where the curvature (second derivative) of the E-k curve is maximal.

## 5

### (a)

* Sign of Majority Carriers: Use the Hall effect. The sign of the Hall voltage indicates the charge carrier type.

* Carrier Concentration: Hall effect measurements can also determine the carrier concentration by measuring the magnitude of the Hall voltage.

* Band Gap: Photoluminescence spectroscopy or UV-Vis absorption spectroscopy can determine the band gap through the onset of absorption.

* Mobility of Majority Carriers: Field-effect transistor (FET) measurements or Hall effect measurements can calculate carrier mobility.

### (b)

In an intrinsic semiconductor, the conductivity increases with temperature. This is because as the temperature rises, more electrons gain enough energy to jump from the valence band to the conduction band, which increases the number of charge carriers available for conduction.

On the other hand, in a metallic conductor, the conductivity typically decreases as temperature increases. As temperature rises, the thermal vibrations of the atomic lattice increase, which leads to more scattering of the conduction electrons, thereby increasing the electrical resistance and reducing the conductivity.

## 6

### (a)

Larmor diamagnetism, also known as Landau diamagnetism, arises from the motion of charged particles, particularly electrons, in response to an applied magnetic field. When a magnetic field is applied, the electron orbits will be slightly shifted due to the force exerted by the magnetic field, which is perpendicular to the velocity of the electron.

According to Larmor's theorem, this results in an induced current. The direction of this induced current will be such that it opposes the change in the magnetic field inside the electron's orbit, according to Lenz's law. The opposition to the change in magnetic field is effectively a diamagnetic response.

This means that Larmor diamagnetism is a property of all materials, because all materials contain electrons, which will react to an external magnetic field in this way. However, in many materials, this diamagnetic response is often overshadowed by other magnetic effects, such as paramagnetism or ferromagnetism.

### (b)

As argon is diamagnetic, The magnetic susceptibility ($\chi$) of argon can be calculated from the formula for Larmor diamagnetism:

$$ \chi_{\rm Larmor} = - \frac{Zne^2\mu_0 \langle r^2\rangle}{6m} $$

where $Z$ is the atomic number of argon: $Z = 18$;

$n$ is the number of atoms per unit volume:

$$ n = \frac{4}{a^3} \approx  2.7485 \rm{m}^{-3} $$

$\langle r^2\rangle$ is the mean square radius:

$$ r \approx (1.88 \rm\r{A})^2 \approx 3.5344 \rm\r{A}^2$$

We can get the result:

$$ \chi_{\rm Larmor} \approx 1.0317\times10^4 $$

## 7

### Superconductivity

Superconductivity is a quantum mechanical phenomenon observed in certain materials, where electrical resistance disappears and magnetic flux fields are expelled from the material below a certain critical temperature, known as the superconducting transition temperature (Tc).

Two key features define superconductivity:

Zero electrical resistance: Below the critical temperature, superconductors carry electric current without any dissipation. This means that an electrical current could continue to circulate in a superconducting loop theoretically forever.

Meissner effect: Superconductors expel magnetic fields from their interior, a phenomenon known as the Meissner effect. As a result, a magnet placed above a superconductor will levitate due to this magnetic field expulsion.

These properties arise from the formation of Cooper pairs, pairs of electrons with opposite momentum and spin, which move through the lattice without scattering off impurities or lattice vibrations (phonons). This pairing mechanism, proposed by Bardeen, Cooper, and Schrieffer, is known as BCS theory, which successfully explains conventional low-temperature superconductivity.
