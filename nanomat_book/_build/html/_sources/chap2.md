# 2. Physical chemsitry of solid surfaces

:::{contents}
:local:
:depth: 2
:::

## 2.2 Surface energy

Atoms or molecules on solid surfaces have fewer nearest neighbors (lower coordination number) compared to in the bulk, thus have areas where bonding can happen exposed to the surface

This leads to:

- Nanomaterials are in general metastable or unstable
- They tend to undergo changes that lower the surface energy

Surface atoms feel an inward-directed force from the bulk $\rightarrow$ for small enough particles lattice parameter show a reduction

### Surface specific energy

The energy (work) required to create a unit area of 'new' surface:

$$
\gamma = \left(\frac{\partial G}{\partial A}\right)_{n_i,T,p} = \frac{dW}{dA}
$$

If we ignore interactions with higher order neighbors, assume that $\epsilon$ is the same for surface and bulk atoms, and we don't include entropic or pressure-volume contributions. Surface energy can be crudely estimated as:

$$
\gamma \approx N_b \left(\frac{\epsilon}{2}\right)\rho_a
$$

$N_b$ is the number of broken bonds.  
$\epsilon$ is the bond strength (J).  
$\rho_a$ is the surface atomic density $\left(\text{m}^{-2}\right)$.

This relation only gives a rough estimation of the true surface energy of a
solid surface, and is only applicable to solids with rigid structure where no
surface relaxation occurs. We can use this to find e.g. that crystal surfaces with low miller indices generally have a lower surface energy than with high miller indices.

### Reducing total surface energy overview

Overview of possible modifications:

- Modifications of a surface with fixed area:

  1. [Relaxation](#relaxation-of-the-surface)
  2. [Restructuring](#restructuring-of-surface-atoms)
  3. [Adsorption](#chemical-or-physical-adsorption-on-surface)
  4. [Compositional segregation](#composition-segregation)

- Modifications of the shape of and individual particle:

  1. [Minimization of surface area](#minimization-of-surface-area)
  2. [Formation of low-energy facets](#formation-of-low-energy-facets)

- Modification of the system (combining particles):
  1. [Sintering](#sintering)
  2. [Ostwald ripening](#ostwald-ripening)
  3. [Agglomeration](#agglomeration)

### Modifications of a surface with fixed area

#### Relaxation of the surface

Can shift inward or lateral so that bond length become shorter as shown in {numref}`fig_surf_relax`.

:::{figure-md} fig_surf_relax
![surf_relax](images/surface_relaxation.png)

Schematic showing surface atoms shifting either inwardly or laterally so as to
reduce the surface energy.
:::

#### Restructuring of surface atoms

Reducing the amount of dangling bonds by restructuring shown in {numref}`fig_restructuring`

:::{figure-md} fig_restructuring
![restructuring](images/restructuring.png)

Schematic illustrating the (2 X 1) restructure of silicon {100) surface.
:::

#### Chemical or physical adsorption on surface

:::{figure-md} fig_adsorption
![adsorption](images/adsorption.png)

Schematic showing the surface of diamond is covered with hydrogen and that of
silicon is covered with hydroxyl groups through chemisorption before restructuring..
:::

#### Composition segregation

Composition segregation or enrichment of impurities on the surface is another way to reduce surface energy. Enrichment on the surface through solid state diffusion might play a role in nanoparticles

### Modifications of the shape of and individual particle

#### Minimization of surface area

Liquids and solids form spherical droplets because this minimizes the surface area and therefore the surface energy.

#### Formation of low-energy facets

Crystalline structures form as faceted crystals because the surface energy is not isotropic (the same in all directions) and certain crystallographic planes have lower energy.

##### Wulff construction

The lowest energy shape can be determined by Wulf construction:

For an equilibrium crystal, i.e. the total surface
energy reaches minimum, there exists a point in the interior such that its perpendicular distance, $h_i$, from the $i$th face is proportional to the surface energy $\gamma_i$:

$$
\gamma_i = Ch_i
$$

Where C is a constant. For a given crystal, C is the same for all the surfaces. A Wulff plot can be constructed by:

1. Given a set of surface energies for the various crystal faces, draw a set of vectors from a common point of length proportional to the surface
   energy and direction normal to that the crystal face.
2. Construct the set of faces normal to each vector and positioned at its
   end.
3. Find a geometric figure whose sides are made up entirely from a particular
   set of such faces.

{numref}`fig_wulff` shows a 2D example of how one would construct a Wulff plot.

:::{figure-md} fig_wulff
![wulff](images/wulff.png)

Conformation for a hypothetical two-dimensional crystal. (a) (10) plane, (b) (11)
plane, (c) shape given by the Wulff construction, and (d) Wulff construction considering
only (10) and (11) planes. [A.W. Adamson and A.P. Gast, Physical Chemistry of Surfaces,
6th edition, John Wiley & Sons, New York, 1997].
:::

##### Surface roughening

At high enough temperatures, the equilibrium crystal may not be smooth, and differences in surface energy of different crystal facets might disappear. This transition is called surface roughening or roughening transition. Below the roughening temperature the crystal is faceted. While above the roughening temperature the crystal surface can be considered liquid, and the difference in energy between different crystal facets becomes negligible compared to thermal motion.

##### Kinetic factors

Kinetic factors may also prevent the formation of facets

### Modification of the system

#### Sintering

Individual structures merge together, which occurs at ca. 70% of $T_m$. Replacing solid-vapor interface by solid-solid interface and becomes polycrystalline as shown in {numref}`fig_sintering`.
:::{figure-md} fig_sintering
![sintering](images/sintering.png)

Schematic showing sintering process. Sintering is to
combine individual particles to a bulk with solid interfaces to connect each other. This process reduces the solid-gas surface area.
:::

#### Ostwald ripening

Lager particles grow at the expense of smaller ones. Occurs at relatively low temperatures (Shown in {numref}`fig_ostwald`).

:::{figure-md} fig_ostwald
![ostwald](images/ostwald_ripening.png)

Schematic showing ostwald ripening process. Ostwald ripening is to merge smaller particles into larger ones. This process reduces the solid-gas surface area.
:::

#### Agglomeration

Individual nanostructures cluster without altering the individual nanostructures (no mass transport). The smaller the particles, the greater the bonding forces.

### Energy in different facets

TBA

## 2.3 Chemical potential as a function of surface curvature

As discussed in previous sections, the properties of surface atoms or molecules
are different from that of interior atoms or molecules, due to fewer
bonds linking to their nearest neighbor atoms or molecules as compared
with their interior counterparts. Further, the chemical potential is also
dependent on the radius of curvature of a surface.

$$
\Delta µ = µ_c - µ_{\infty} = 2\gamma\frac{\Omega}{R} = \gamma\Omega\left(\frac{1}{R_1}+\frac{1}{R_2}\right) \quad \text{(Young-Laplace equation)}
$$

$R$ is particle radius.  
$\Omega$ is atomic volume.  
$\Delta µ$ is work per atom transferred.  
$µ_c$ is the chemical potential at particle surface.  
$µ_\infty$ is the chemical potential on flat surface.
$R_1, R_2$ are the principal radii of curvature.

Radius of curvature is explained in {numref}`fig_curvature`

:::{figure-md} fig_curvature
![curvature](images/curvature.png)

Figure showing radius of curvature.
:::

For a convex surface, the curvature is positive, and thus the chemical potential of atoms here is higher than a flat surface. For a concave surface, the curvature is negative, and the chemical potential is lower than a flat surface as shown in {numref}`fig_curvature_energy`.

:::{figure-md} fig_curvature_energy
![curvature_energy](images/curvature_energy.png)

Variation in solubility of silica with radius of curvature of surface. The positive
radii of curvature are shown in cross-section as particles and projections from a planar surface;
negative radii are shown as depressions or holes in the surface, and in the crevice
between two particles. [R.K. Her, The Chemistry of Silica, Wiley, New York, 1979].
:::

## 2.4 Electrostatic stabilization

Concerning how to prevent nanostructures from agglomerating. A system using electrostatic stabilization in kinetically stable.

### Surface charge density

When a solid emerges in a polar solvent or an electrolyte solution, a
surface charge will be developed through one or more of the following
mechanisms:

1. Preferential adsorption of ions
2. Dissociation of surface charged species
3. Isomorphic distribution of ions
4. Accumulation or depletion of electrons on the surface
5. Physical adsorption of charged species onto the surface

For a given solid surface in a given liquid
medium, a fixed surface electrical charge
density or electrode potential E will be
established, and this is described by Nernst
equation:

$$
E = E_0 + \frac{RT}{n_iF}\ln a_i
$$

$E_0$ is the standard electrode potential when the concentration of ions is unity.  
$n_i$ is the valence state of ions.  
$a_i$ is the activity of ions.  
$R$ is the gas constant.  
$T$ is the temperature.  
$F$ is the Faraday constant.

Surface potential of a solid varies with the concentration of the ions surrounding solution, and can be negative or positive.

#### Point of zero charge (PZC)

We are focusing on non-conducting metals, specifically oxides.
Ions adsorbed on the surface determine the surface charge, and are therefore referred to as charge determining ions. As the concentration of these ions vary, the surface charge density $\left(E\right)$ changes between positive and negative. The concentration of ions that lead to a neutral (zero-charged) surface is defined as the point of zero charge (PZC).

At pH > PZC, the oxide surface is negatively charged since the surface is covered with charge determining hydroxyl groups (OH$^{-1}$). for pH < PZC the surface is positively charged, and the charge determining species is H$^+$

### Electric potential at the proximity of a solid surface

The surface charge density leads to inhomogeneous distributions of charge determining ions and oppositely charged counter ions. The distributions are mainly controlled by a combination of the following forces:

1. Coulombic force or electrostatic force
2. Entropic force or dispersion
3. Brownian motion

This leads to the formation of a double layer structure shown in {numref}`fig_double_layer`.

:::{figure-md} fig_double_layer
![double_layer](images/doublelayer.png)

Schematic illustrating electrical double layer structure and the electric potential
near the solid surface with both Stem and Gouy layers indicated. Surface charge is
assumed to be positive.
:::

The zeta potential is the potential at the slip plane.

This potential can be determined by the following steps:

1. Apply an electric field
2. Measure the particle velocity, e.g., by measuring dopplershift of scattered light
3. Calculate the electrophoretic mobility:

$$
µ_e = \frac{V}{E}
$$

The measured potential depends on the zeta potential (The smoluchovski model):

$$
µ_e = \frac{\epsilon_r\epsilon_0\zeta}{\eta(T)}
$$

### Interactions between two particles: DLVO theory

The total interaction energy between two particles, which are electrostatically stabilized,
is the combination of van der Waals attraction and electrostatic repulsion:

$$
\Phi = \Phi_A + \Phi_R
$$

Some important assumptions:

1. Infinite flat solid surface.
2. Uniform surface charge density.
3. No redistribution of surface charge, i.e. the surface electric potential
   remains constant.
4. No change of concentration profiles of both counter ions and surface
   charge determining ions, i.e. the electric potential remains
   unchanged.
5. Solvent exerts influences via dielectric constant only, i.e. no chemical
   reactions between the particles and solvent.

Schematic of DLVO potential is shown in {numref}`fig_DLVO_single`.

:::{figure-md} fig_DLVO_single
![DLVO_single](images/DLVO_single.png)

Schematic of DLVO potential: V$_A$ = attractive van der Waals potential,
V$_R$, = repulsive electrostatic potential.
:::

And total interaction between two spherical particles for different double layer thickness is shown in {numref}`fig_DLVO_multi`.

:::{figure-md} fig_DLVO_multi
![DLVO_multi](images/DLVO_multi.png)

Variation of the total interaction energy $\Phi$ between two spherical particles, as a
function of the closest separation distance S$_0$ between their surfaces, for different double
layer thickness $\kappa^{-1}$ obtained with different monovalent electrolyte concentrations. [J.T.G. Overbeek, .J Colloid
Inter- Sci. 58, 408 (1977)].
:::

### Limitations of electrostatic stabilization

1. Only works for dilute systems
2. Its electrolyte sensitive
3. Close to impossible to re-disperse agglomerated particles
4. Difficult to apply to multiphase system, since in a given condition, different solids develop different surface charge and electric potential.

## 2.5 Steric stabilization

Steric stabilization, also called polymeric stabilization is a method widely
used in stabilization of colloidal dispersions. It functions by attaching polymers to a surface. The polymers can be anchored (irreversibly bound to the surface) or adsorbed (adsorbed weakly at random points along the polymer backbone).

### Advantages over electrostatic stabilization

1. It is a thermodynamic stabilization method, so the particles are
   always redispersible.
2. A very high concentration can be accommodated, and the dispersion
   medium can be completely depleted.
3. It is not electrolyte sensitive.
4. It is suitable for multiple phase systems.

### Interaction between polymer layers

{numref}`fig_steric` shows the interaction between polymer layers when the solvent is **good**, and the polymers expand to reduce the overall Gibbs free energy of the system.

:::{figure-md} fig_steric
![steric](images/steric.png)

Schematic of interactions between polymer layers: (a) the schematic of two
approaching polymer layers, and (b) the Gibbs free energy as a function of the distance
between two particles.
:::

{numref}`fig_steric2` shows the interaction between polymer layers when the solvent is **bad**, and the polymers coil up in order to reduce the free energy.

:::{figure-md} fig_steric2
![steric2](images/steric2.png)

Schematic of interactions between polymer layers: (a) the schematic of two
approaching polymer layers, and (b) the Gibbs free energy as a function of the distance
between two particles.
:::

### Electrosteric stabilization

Combination of steric and electrostatic stabilization as shown in {numref}`fig_electrosteric`. Can be charged particles with uncharged polymers, or uncharged particles with charged polymers.

:::{figure-md} fig_electrosteric
![electrosteric](images/electrosteric.png)

Schematic representation of electrosteric stabilization: (a) charged particles
with non-ionic polymers and (b) polyelectrolytes attached to uncharged particles.
:::
