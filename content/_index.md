---
title: Home
date: 2024-01-01
type: landing

sections:
  - block: hero
    content:
      title: "Domina la Física"
      # Usamos etiquetas HTML para forzar el tamaño y el peso de la letra
      text: |
        <h2 style="font-size: 2.2rem; line-height: 1.2; margin-bottom: 1.5rem; font-weight: 700;">
          Providing free resources for a rigorous and comprehensive understanding of physics.
        </h2>
        <p style="font-size: 1.3rem; opacity: 0.9;">
          Focusing on problem solving as well as formal mathematical derivations and demonstrations.
        </p>
      cta:
        label: Physics Notes
        url: docs/
      image:
        filename: dominalafisica_logo.jpg
    design:
      background:
        color: '#1e3a8a'
        text_color_light: true
      spacing:
        padding: ['120px', '0', '120px', '0']

  - block: features
    content:
      title: "About the Project"
      items:
        - name: "Rigorous Derivations"
          description: "Focus on formal mathematical proofs and analytical methods."
          icon: book-open
          icon_pack: fas
        - name: "Problem Solving"
          description: "Step-by-step solutions to complex physical problems."
          icon: pencil-alt
          icon_pack: fas
        - name: "Open Access"
          description: "High-quality resources for the global physics community."
          icon: unlock-alt
          icon_pack: fas
    design:
      columns: '3'
      spacing:
        padding: ['80px', '0', '80px', '0']

  - block: markdown
    content:
      title: "Featured Physics Topics"
      subtitle: "Explore our in-depth analytical guides."
      text: |
        We are currently developing comprehensive notes for advanced undergraduate and graduate physics. New content is added weekly.

        - **[Mathematical Methods](/docs/mathematical-methods/):** Analytical tools and complete derivations, including the Bessel differential equation.
        - **Electrodynamics (Upcoming):** Boundary value problems and Maxwell's equations.
        - **Quantum Mechanics (Upcoming):** Advanced formalisms and many-body physics.
    design:
      spacing:
        padding: ['80px', '0', '80px', '0']
---
