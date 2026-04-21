---
title: Home
date: 2024-01-01
type: landing

sections:
  - block: hero
    content:
      title: "Domina la Física"
      text: |
        <h2 style="font-size: 2.4rem; font-weight: 400; line-height: 1.3; margin-top: 80px; margin-bottom: 1rem;">
          Providing free resources for a rigorous and comprehensive understanding of physics.
        </h2>
        <p style="font-size: 1.4rem; font-weight: 300; opacity: 0.9;">
          Focusing on problem solving as well as formal mathematical derivations and demonstrations.
        </p>
      cta:
        label: Physics Notes
        url: docs/
    design:
      background:
        color: '#1e3a8a'
        text_color_light: true
      spacing:
        # El 20px inicial sube el título hacia la barra de navegación
        padding: ['20px', '0', '100px', '0']

  - block: features
    content:
      title: "About the Project"
      items:
        - name: "Rigorous Derivations"
          description: "Focus on mathematical proofs and analytical methods."
          icon: book-open
        - name: "Problem Solving"
          description: "Step-by-step solutions to complex physical problems."
          icon: pencil
        - name: "Open Access"
          description: "High-quality resources for the global physics community."
          icon: users
    design:
      columns: '3'
      spacing:
        padding: ['80px', '0', '80px', '0']

  - block: markdown
    content:
      title: "Featured Physics Topics"
      subtitle: ""
      text: |
        Currently developing comprehensive notes for undergraduate and graduate physics.

        - **Mathematical Methods:**Differential equations, special functions, vector analysis, and analytical tools..
        - **Classical Electrodynamics :** Field and potential problems, boundary-value problems, multipole expansions, and Maxwell's equations.
        - **Classical Mechanics:** Newtonian, Lagrangian, and Hamiltonian formulations, as well as rigid body dynamics.
        - **Quantum Mechanics:** Wave mechanics, formalism, and advanced quantum systems.
    design:
      spacing:
        padding: ['80px', '0', '80px', '0']
---
