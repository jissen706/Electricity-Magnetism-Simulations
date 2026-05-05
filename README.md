# Electricity & Magnetism — Interactive Simulations

A growing collection of self-contained HTML simulations for PHYS 151. Each file is standalone — open it in any modern browser, no server or build step.

## Modules

### 1. `molecular_polarization.html` — Molecular Model of Polarization (Chunk 5)
1. **Free vs. Bound charges** — Conductor (free electrons) vs. dielectric (bound electrons). "Material" dropdown.
2. **Polar vs. Nonpolar molecules** — Polar molecules (e.g. H₂O) align with **E**; nonpolar develop an induced dipole. Dropdown + field-strength slider.
3. **Bound surface charges** — Polarized slab with σᵢ⁺ / σᵢ⁻ on surfaces, neutral bulk. "Polarization strength" slider.
4. **Opposing electric field** — **E₀**, **Eᵢ**, and **E_net = E₀ − Eᵢ**. Sliders for external field and κ.

### 2. `magnetic_flux.html` — Magnetic Flux & Orientation
1. **Flux Orientation** — Tilt a loop in a uniform **B** field. Live readout of Φ = BA cos θ. Field lines threading the loop are highlighted. Sliders: θ, |B|, area.
2. **Rotating Loop (Φ vs t)** — Loop spins at angular speed ω; flux traces a cosine in real time. Sets up Faraday's law / AC generators.

### 3. `lenz_law.html` — Lenz's Law (Chunk 3)
1. **Bar magnet & loop** — Push a bar magnet toward / away from a loop and watch the induced current direction flip to oppose the change in flux. Live Φ(t) and induced-current readouts.
2. **Loop entering/leaving a B region** — Drag a loop in and out of a uniform field zone; induced EMF and current direction update with the changing flux.

### 4. `em_waves.html` — Electromagnetic Waves
1. **Wave structure** — 3D view of an EM wave with **E** ⊥ **B** ⊥ direction of propagation. Verifies c = fλ with sliders for frequency and wavelength.
2. **Point vs. snapshot views** — Toggle between watching one point oscillate over Δt = T and a snapshot in space spanning Δx = λ.
3. **Intensity, Poynting vector & radiation pressure** — Vary amplitude / distance and see I, **S**, and P_rad respond.

## How to run

Double-click any `.html` file (or drag it into Chrome / Safari / Firefox). No install required. Use the top navigation in each module to switch between sections.
