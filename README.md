# 🌌 AccretionVibe

### A Herbig Ae/Be Star Disk Simulator

> A visually rich, physically-inspired simulator of circumstellar
> accretion disks around Herbig Ae/Be stars.

AccretionVibe is a lightweight browser-based simulator that visualizes
the **dynamics of protoplanetary disks** around intermediate-mass
pre-main-sequence stars.

It combines **real astrophysical ideas** (dust sublimation rims,
Keplerian rotation, disk flaring, grain settling, accretion flows, and
outflows) with a **clean interactive UI** for exploration and teaching.

Built as a **single HTML + JavaScript project** --- no backend, no build
tools, and no dependencies beyond Tailwind.

------------------------------------------------------------------------

# ✨ Features

The simulator visualizes the **inner few AU of a Herbig star disk**,
including:

-   Differential **Keplerian rotation**
-   **Dust sublimation rim** driven by stellar luminosity
-   **Gas inside the dust cavity**
-   **Flared disk geometry**
-   **Grain settling** (small vs large dust populations)
-   **Accretion drift toward the star**
-   Optional **disk winds or jets**
-   **Inclination effects** on disk appearance
-   **UX Ori occultation behavior**
-   **Transitional disk gaps**

All physics is rendered in **real‑time particle dynamics on an HTML
canvas**.

------------------------------------------------------------------------

# 🔬 Physical Concepts

## Dust Sublimation Radius

The inner disk edge is approximated using the luminosity scaling:

R_sub ∝ √L\_\*

where

L\_\* ∝ R\_*² T\_*⁴

This follows the observed **Herbig size--luminosity relation** seen in
interferometric studies.

------------------------------------------------------------------------

## Keplerian Disk Rotation

Angular velocity approximately follows

Ω ∝ r\^(-3/2)

meaning **inner disk material orbits faster than outer material**,
producing shear in the disk.

------------------------------------------------------------------------

## Grain Settling

Two dust populations are represented:

  Grain Type     Behavior
  -------------- ---------------------------------------------
  Small grains   high scale height, strong scattering
  Large grains   settle toward midplane, faster inward drift

------------------------------------------------------------------------

## Accretion Drift

Radial inward motion is **much slower than orbital motion**, consistent
with viscous accretion disk theory.

------------------------------------------------------------------------

## Disk Geometry

Two observational disk structures are modeled:

**Flared disks** - strong stellar irradiation - bright outer disk -
strong PAH emission

**Self-shadowed disks** - puffed-up inner rim - reduced outer disk
illumination

------------------------------------------------------------------------

# 🎛 Interactive Controls

## Stellar Parameters

  Control          Description
  ---------------- -------------------------------
  Temperature      Stellar effective temperature
  Radius           Stellar radius
  Rotation Scale   Orbital velocity scaling

------------------------------------------------------------------------

## Disk Parameters

  Control           Description
  ----------------- ---------------------------
  Accretion Drift   inward mass flow strength
  Turbulence        vertical disk structure
  Inclination       viewing angle of the disk

------------------------------------------------------------------------

## Source Modes

  Mode                Description
  ------------------- -----------------------------------------
  Herbig Ae           moderate magnetospheric accretion
  Herbig Be           hotter stars with weaker magnetospheres
  Transitional Disk   cavity and dust gap
  UX Ori-like         variable occultation by dusty clumps

------------------------------------------------------------------------

## Outflow Modes

  Mode        Description
  ----------- ------------------------
  None        disk only
  Disk Wind   wide-angle wind
  Jet         collimated bipolar jet

------------------------------------------------------------------------

# 🖥 Running the Simulator

No installation required.

Simply open:

accretionvibe_herbig_aebe_realistic.html

in any modern browser.

Works in:

-   Chrome
-   Firefox
-   Safari
-   Edge

------------------------------------------------------------------------

# 📂 Repository Structure

AccretionVibe/

├── accretionvibe_herbig_aebe_realistic.html\
└── README.md

The entire simulator is **self‑contained in a single HTML file**.

------------------------------------------------------------------------

# 🎨 Design Philosophy

The goal of AccretionVibe is:

**Scientific inspiration + aesthetic immersion**

It is not a hydrodynamic simulation, but a **physics-guided
visualization** designed to help users intuitively understand how
accretion disks around young stars behave.

------------------------------------------------------------------------

# 🚀 Future Improvements

Possible upgrades:

-   PAH emission layer visualization
-   Magnetospheric accretion funnels
-   Synthetic spectral energy distributions (SEDs)
-   Emission-line diagnostics (Hα, Brγ, \[OI\])
-   Planet-induced spiral arms
-   ALMA-style disk imaging mode

------------------------------------------------------------------------

# 👨‍🚀 Author

A vibe‑coded astrophysics visualization project exploring how **stars
and planets form inside circumstellar disks**.
