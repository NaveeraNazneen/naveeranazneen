<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 400" width="400" height="400">
  <defs>
    <radialGradient id="bgGrad" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#302b63"/>
      <stop offset="60%" stop-color="#1a1742"/>
      <stop offset="100%" stop-color="#0f0c29"/>
    </radialGradient>
    <radialGradient id="coreGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#a78bfa"/>
      <stop offset="40%" stop-color="#7c3aed"/>
      <stop offset="100%" stop-color="#4c1d95"/>
    </radialGradient>
    <radialGradient id="ringGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#c4b5fd" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#7c3aed" stop-opacity="0.3"/>
    </radialGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="softGlow">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background circle -->
  <circle cx="200" cy="200" r="196" fill="url(#bgGrad)" stroke="#4c1d95" stroke-width="1.5"/>

  <!-- Outer orbit ring -->
  <ellipse cx="200" cy="200" rx="155" ry="155" fill="none" stroke="#6d28d9" stroke-width="0.8" stroke-dasharray="4 6" opacity="0.5"/>

  <!-- Mid orbit ring -->
  <ellipse cx="200" cy="200" rx="115" ry="115" fill="none" stroke="#7c3aed" stroke-width="0.6" stroke-dasharray="3 8" opacity="0.4"/>

  <!-- Electron orbit path 1 (tilted) -->
  <ellipse cx="200" cy="200" rx="90" ry="35" fill="none" stroke="#a78bfa" stroke-width="1.2" opacity="0.7" transform="rotate(-30 200 200)" filter="url(#glow)"/>

  <!-- Electron orbit path 2 (tilted other way) -->
  <ellipse cx="200" cy="200" rx="90" ry="35" fill="none" stroke="#a78bfa" stroke-width="1.2" opacity="0.7" transform="rotate(30 200 200)" filter="url(#glow)"/>

  <!-- Electron orbit path 3 (horizontal) -->
  <ellipse cx="200" cy="200" rx="90" ry="35" fill="none" stroke="#c4b5fd" stroke-width="1" opacity="0.5"/>

  <!-- Electrons on orbits -->
  <circle cx="290" cy="200" r="5" fill="#c4b5fd" filter="url(#glow)"/>
  <circle cx="155" cy="157" r="4" fill="#e879f9" filter="url(#glow)"/>
  <circle cx="248" cy="243" r="3.5" fill="#818cf8" filter="url(#glow)"/>

  <!-- Core atom nucleus -->
  <circle cx="200" cy="200" r="28" fill="url(#coreGlow)" filter="url(#softGlow)"/>
  <circle cx="200" cy="200" r="20" fill="#7c3aed" opacity="0.9"/>

  <!-- Stars scattered around -->
  <circle cx="60" cy="70" r="1.5" fill="white" opacity="0.8"/>
  <circle cx="340" cy="55" r="1" fill="white" opacity="0.6"/>
  <circle cx="355" cy="140" r="1.5" fill="#c4b5fd" opacity="0.7"/>
  <circle cx="45" cy="310" r="1" fill="white" opacity="0.5"/>
  <circle cx="370" cy="340" r="1.5" fill="white" opacity="0.8"/>
  <circle cx="80" cy="350" r="1" fill="#a78bfa" opacity="0.6"/>
  <circle cx="320" cy="350" r="1.5" fill="white" opacity="0.5"/>
  <circle cx="130" cy="50" r="1" fill="#c4b5fd" opacity="0.7"/>
  <circle cx="290" cy="45" r="1.5" fill="white" opacity="0.6"/>

  <!-- Monogram "NN" in nucleus -->
  <text x="200" y="207" text-anchor="middle" dominant-baseline="middle"
        font-family="Georgia, serif" font-size="16" font-weight="700"
        fill="#ede9fe" letter-spacing="2" filter="url(#glow)">NN</text>

  <!-- Name text -->
  <text x="200" y="290" text-anchor="middle"
        font-family="Georgia, 'Times New Roman', serif"
        font-size="18" font-weight="600" fill="#c4b5fd"
        letter-spacing="3" filter="url(#glow)">NAVEERA NAZNEEN</text>

  <!-- Tagline -->
  <text x="200" y="316" text-anchor="middle"
        font-family="'Courier New', monospace"
        font-size="9.5" fill="#7c3aed" letter-spacing="2.5" opacity="0.9">PHYSICIST  ·  DEVELOPER  ·  SPACE</text>

  <!-- Bottom decorative line -->
  <line x1="120" y1="328" x2="280" y2="328" stroke="#6d28d9" stroke-width="0.8" opacity="0.6"/>

  <!-- Tiny sigma / equation hint at bottom -->
  <text x="200" y="348" text-anchor="middle"
        font-family="Georgia, serif"
        font-size="11" fill="#6d28d9" opacity="0.7" letter-spacing="1">∇²ψ + k²ψ = 0</text>
</svg>
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=120&section=header" width="100%"/>

<br/>

<!-- LOGO — place logo.svg in root of this repo and it will show here -->
<img src="logo.svg" alt="Naveera Nazneen" width="200"/>

<br/><br/>

# Naveera Nazneen
### Experimental & Computational Physicist · App Developer · Future Space Agency Scientist

<br/>

[![Email](https://img.shields.io/badge/naveeranazneen21%40gmail.com-302b63?style=flat-square&logo=gmail&logoColor=white)](mailto:naveeranazneen21@gmail.com)
[![GitHub](https://img.shields.io/badge/github.com/naveeranazneen-0f0c29?style=flat-square&logo=github&logoColor=white)](https://github.com/naveeranazneen)

</div>

---

## About Me

I am an experimental and computational physicist with a focus on nanomaterials, photocatalysis, and physics simulation.

My research spans the synthesis and characterisation of advanced nanocomposites — including work on RGO–La₂O₃–SnO₂ ternary heterojunction photocatalysts — with hands-on expertise across XRD, UV-Vis, FTIR, and SEM/EDX characterisation.

Outside the lab, I build and ship full-stack applications independently, integrating tools like the Anthropic Claude API as intelligent middleware to create smarter research tools and productivity software — I handle the architecture, code, configuration, and deployment end-to-end.

My long-term goal is to contribute to space science and work at a space agency. Every project is a step in that direction.

---

## Experimental Physics

I work at the interface of nanomaterials science and photophysics, with practical experience in:

Synthesis and structural characterisation of ternary and binary heterojunction nanocomposite systems with engineered bandgap properties.

XRD phase identification, crystallite size determination using the Scherrer equation, and Bragg's law analysis.

UV-Vis spectroscopy and Tauc plot construction for optical bandgap extraction in semiconductor nanomaterials.

Photocatalytic degradation kinetics — pseudo-first-order modelling for dye systems (methyl orange and related compounds) under UV and visible light.

FTIR spectroscopy for functional group identification and surface chemistry analysis.

SEM/EDX for morphology characterisation and elemental mapping.

BET surface area analysis for porous and nanostructured materials.

---

## Computational Physics & Simulation

I build physics simulations from first principles — translating differential equations and physical laws into working, quantitatively accurate computational models.

I am advancing my expertise in COMSOL Multiphysics for finite element analysis across electromagnetic, thermal, fluid, and coupled multiphysics domains.

I use LAMMPS (Large-scale Atomic/Massively Parallel Simulator) for molecular dynamics simulations, including interatomic potential setup, ensemble selection (NVT, NPT, NVE), thermostat/barostat configuration, and trajectory post-processing.

My simulation work covers classical mechanics, thermodynamics, quantum systems, and electromagnetism — all implemented with physical rigour.

---

## Programming & Technical Stack

**Languages**

I write scientific and systems-level code in C++, Python, and MATLAB.

In C++ I build physics engines, implement numerical integrators (Runge-Kutta 4, Velocity Verlet, Leapfrog), write finite difference solvers, and work at the performance layer where memory control matters.

In Python I work with NumPy, SciPy, Matplotlib, Pandas, and SymPy for data pipelines, signal processing, symbolic computation, and simulation scripting. I also use Python to interface with APIs and build backend logic for applications.

In MATLAB I handle matrix operations, system dynamics modelling, signal analysis, and rapid numerical prototyping.

For web interfaces I write HTML, CSS, and JavaScript to build clean, functional frontends — including dashboards and interactive simulation visualisers.

**Simulation & Modelling Tools**

LAMMPS — atomistic molecular dynamics, force field configuration, DUMP file parsing and analysis.

COMSOL Multiphysics — multiphysics FEA, parametric sweeps, mesh refinement, solver configuration.

**App Development**

I independently build and deploy full-stack web applications and research tools.

I integrate AI APIs — including the Anthropic Claude API — as intelligent middleware: using model capabilities programmatically to power smarter tools while I handle all architecture, logic, deployment, and maintenance.

GitHub Student Developer Pack — actively using the developer toolchain for version control, project management, and CI workflows.

**Other Tools**

Git & GitHub · LaTeX · Origin Pro · Mendeley · VSCode · Linux/Ubuntu

---

## Currently Building

Physics simulations in C++ and Python modelling quantum and classical systems with real physical accuracy.

COMSOL and LAMMPS workflows for nanomaterial characterisation and molecular dynamics.

AI-powered research and productivity tools using the Anthropic Claude API as a backend intelligence layer.

Expanding into computational astrophysics and orbital mechanics — feeding directly into the long game.

---

## The Long Game

The end goal is space.

Propulsion physics, spacecraft materials, mission simulation, remote sensing — the domain is open, the direction is fixed.

Everything I build is part of that foundation.

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=80&section=footer" width="100%"/>
<sub>naveeranazneen21@gmail.com · github.com/naveeranazneen</sub>
</div>
