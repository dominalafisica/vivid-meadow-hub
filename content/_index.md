---
title: Home
date: 2024-01-01
type: landing

sections:
  - block: hero
    content:
      title: "Domina la Física"
      text: |
        <div style="font-size: 3.5rem; font-weight: 400; line-height: 1.2; margin-bottom: 1.5rem; width: 100%; max-width: 100%;">
          Providing free resources for a rigorous and comprehensive understanding of physics.
        </div>
        <div style="font-size: 1.8rem; font-weight: 300; opacity: 0.9; width: 100%; max-width: 100%;">
          Focusing on problem solving as well as formal mathematical derivations and demonstrations.
        </div>
      cta:
        label: Physics Notes
        url: docs/
    design:
      background:
        color: '#1e3a8a'
        text_color_light: true
      spacing:
        # El primer valor es el espacio de ARRIBA (lo bajamos de 120px a 40px)
        padding: ['40px', '0', '120px', '0']

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
          icon: pencil
          icon_pack: fas
        - name: "Open Access"
          description: "High-quality resources for the global physics community."
          icon: globe
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
