# Collection of Code Files for Physicists

This repository houses a comprehensive collection of code files, notebooks, and numerical tools tailored for theoretical and computational physics. The material is primarily focused on General Relativity, Cosmology, Physics of Compact Objects (Neutron Stars, Black Holes), and abstract Tensor Calculus.

The codebase spans multiple languages and environments, including **Mathematica** (making heavy use of `xAct` and the Black Hole Perturbation Toolkit), **Python**, **Julia**, and **Fortran**.

## Directory Structure

### `GR_v2/`
Contains customized Mathematica packages (`.wl`) and notebooks designed for General Relativity calculations, including routines for computing properties of the Schwarzschild geometry.

### `Mathematica.codes-main/`
Mathematica snippets and analytical/numerical calculations. E.g., studies on the tidal properties of neutron stars in scalar-tensor theories of gravity.

### `MathematicaToolkitExamples-master/`
Notebooks and scripts addressing Black Hole perturbation, Post-Newtonian theory, and self-force calculations. Features computations for fluxes, high-frequency SWSH, and parallel transport in Kerr spacetime.

### `notebooks-main/`
Primarily cosmology and modified gravity notebooks. Covers:
- Cosmological dynamics and FRW metrics
- Stealth black holes and quadratic actions (KGB)
- Tutorials from cosmology workshops

### `Physics-Of-Compact-Objects-main/`
Assignments, solutions, and tutorials focused on the Physics of Compact Objects. Discusses phenomena such as mass-radius relationships, stellar homology, Tolman-Oppenheimer-Volkoff (TOV) equations for various equations of state (SLy, Polytropic), and geodesics (using Python, Julia, and Mathematica).

### `Tidal_Grav_Atoms-main/`
Includes calculations tailored to the tidal properties and tidal Love numbers for "gravitational atoms".

### `tovsolver-master/`
A sophisticated numerical solver combining a Fortran backend and Python frontend. It solves the TOV stellar structure equations for multi-fluid/QCD/MIT bag models and interpolates different equations of state natively.

### `xCoba/`
Contains Mathematica notebooks for coordinate-based calculations in General Relativity, featuring templates and documentation for working with coordinate systems and spacetime metrics.

### `xAct-Mathematica-template-notebooks-for-physics-main/`
Starter Mathematica templates for the `xAct` tensor algebra system. Useful for initiating new projects in tensor calculus, featuring 3+1 splits and GR propagators.

## Standalone Files
- **`xActLearning.nb`**: An extensive tutorial notebook for mastering the `xAct` packages in Mathematica.
- **`RGTC.zip`**: An archive relating to Riemannian Geometry & Tensor Calculus materials or packages.

---
*Please check individual subdirectories for more specific `README.md` files, dependencies, setup instructions, and licensing.*
