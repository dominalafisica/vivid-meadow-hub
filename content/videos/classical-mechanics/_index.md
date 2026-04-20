---
title: "Classical Mechanics"
type: landing

sections:
  - block: markdown
    content:
      title: "Classical Mechanics"
      subtitle: "From Newtonian principles to Lagrangian and Hamiltonian formalisms."
      text: |
        [⬅ Back to Video Lectures](/videos/)

        <div class="expand-container">
        <div class="video-grid">
        <div class="video-wrapper">
        {{< youtube "1U-0f0bgIUM" >}}
        </div>
        <div>
        <h3 style="margin-top: 0;">Particle Sliding on a Rotating Plane | Lagrangian & Equation of Motion</h3>
        <p><strong>Description:</strong><br>
        <em>A step-by-step derivation of the equation of motion for a particle on a rotating plane, demonstrating the power of the Lagrangian formulation in non-inertial frames.</em></p>
        <details>
        <summary><span style="color:#3b82f6; cursor:pointer; font-weight:bold;">Read full description...</span></summary>
        <div style="margin-top: 10px; font-style: italic; font-size: 0.95rem;">
        In this lecture, we tackle a classic problem involving a time-dependent constraint: a particle sliding on a plane that rotates with a constant angular speed. Rather than grappling with the complex fictitious forces (such as Coriolis and centrifugal forces) required by Newtonian mechanics in a non-inertial reference frame, we employ Analytical Mechanics. We formulate the Lagrangian ($\mathcal{L} = T - U$) using generalized coordinates, apply the Euler-Lagrange equation, and solve the resulting second-order linear ordinary differential equation (ODE) via the indeterminate coefficient method to obtain the exact trajectory of the particle.
        </div>
        </details>
        </div>
        </div>
        </div>
        
        <hr style="opacity: 0.1; margin: 4rem 0;">

        <div class="expand-container">
        <div class="video-grid">
        <div class="video-wrapper">
        {{< youtube "gjPqvL2nq2I" >}}
        </div>
        <div>
        <h3 style="margin-top: 0;">Kepler's Second Law | Lagrangian Mechanics & Angular Momentum</h3>
        <p><strong>Description:</strong><br>
        <em>A clear derivation of Kepler's Law of Areas, demonstrating how a central potential leads to the conservation of angular momentum.</em></p>
        <details>
        <summary><span style="color:#3b82f6; cursor:pointer; font-weight:bold;">Read full description...</span></summary>
        <div style="margin-top: 10px; font-style: italic; font-size: 0.95rem;">
        In this lecture, we derive Kepler's Second Law using the Lagrangian formulation. By evaluating the Euler-Lagrange equation for the angular degree of freedom, we prove that because the gravitational potential is purely central, the time derivative of the generalized momentum is zero, strictly enforcing the conservation of angular momentum. We then employ a differential geometric argument modeling the swept area as a differential triangle to evaluate the areal velocity ($dA/dt$). The derivation concludes by explaining the fundamental physical consequence of this law: to maintain a constant areal velocity, a planet must travel faster when closer to the Sun and slower when further away.
        </div>
        </details>
        </div>
        </div>
        </div>
        
        <hr style="opacity: 0.1; margin: 4rem 0;">

        <div class="expand-container">
        <div class="video-grid">
        <div class="video-wrapper">
        {{< youtube "WwNVBrkEJCQ" >}}
        </div>
        <div>
        <h3 style="margin-top: 0;">Escape Velocity | Conservation of Energy</h3>
        <p><strong>Description:</strong><br>
        <em>A quick, intuitive derivation of the escape velocity formula using the conservation of mechanical energy.</em></p>
        <details>
        <summary><span style="color:#3b82f6; cursor:pointer; font-weight:bold;">Read full description...</span></summary>
        <div style="margin-top: 10px; font-style: italic; font-size: 0.95rem;">
        In this concise lecture, we derive the classic formula for escape speed ($v_e = \sqrt{2GM/R}$) by applying the principle of conservation of mechanical energy. To find the absolute minimum speed required, we intuitively set the final kinetic energy to zero at an infinite distance, noting that any excess energy would simply take the object to "infinity and beyond". We briefly show that the limit of the gravitational potential as distance approaches infinity is zero. The video concludes with a quick, interesting physical application: how a planet's escape speed determines its ability to retain an atmosphere and sustain life.
        </div>
        </details>
        </div>
        </div>
        </div>
        
        <hr style="opacity: 0.1; margin: 4rem 0;">

        <div class="expand-container">
        <div class="video-grid">
        <div class="video-wrapper">
        {{< youtube "Z3d1fXklpeU" >}}
        </div>
        <div>
        <h3 style="margin-top: 0;">The General Double Pendulum | Lagrangian & Normal Modes</h3>
        <p><strong>Description:</strong><br>
        <em>A comprehensive, rigorous derivation of the double pendulum system, progressing from the general Lagrangian to the extraction of normal modes of vibration.</em></p>
        <details>
        <summary><span style="color:#3b82f6; cursor:pointer; font-weight:bold;">Read full description...</span></summary>
        <div style="margin-top: 10px; font-style: italic; font-size: 0.95rem;">
        In this extensive class, we tackle one of the most iconic coupled systems in Analytical Mechanics: the double pendulum. Unlike standard textbook treatments that immediately simplify to symmetric conditions, this lecture rigorously derives the equations of motion for the <em>general</em> case (arbitrary masses $m_1, m_2$ and lengths $l_1, l_2$) using the Lagrangian formulation. We then apply the small-angle approximation to linearize the coupled differential equations, setting up the eigenvalue problem to determine the normal frequencies and normal modes of vibration. Finally, we apply these generalized results to the symmetric case, providing a complete analytical picture of the system's oscillatory behavior.
        </div>
        </details>
        </div>
        </div>
        </div>
        
        <hr style="opacity: 0.1; margin: 4rem 0;">

        <div class="expand-container">
        <div class="video-grid">
        <div class="video-wrapper">
        {{< youtube "E59RoG1t7og" >}}
        </div>
        <div>
        <h3 style="margin-top: 0;">1D Wave Equation: Non-Trivial Initial Displacement | PDE Superposition Principle</h3>
        <p><strong>Description:</strong><br>
        <em>A rigorous analytical solution to the 1D wave equation for a vibrating string, from boundary conditions to the exact series solution using orthogonality.</em></p>
        <details>
        <summary><span style="color:#3b82f6; cursor:pointer; font-weight:bold;">Read full description...</span></summary>
        <div style="margin-top: 10px; font-style: italic; font-size: 0.95rem;">
        In this comprehensive lecture, we solve the classic boundary value problem of a vibrating string with fixed ends, released from rest with a specific piecewise initial displacement. The methodology rigorously follows the technique of separation of variables to decompose the 1D wave equation into spatial and temporal ordinary differential equations. After applying the Dirichlet boundary conditions, we invoke the superposition principle to construct the general series solution. Finally, we determine the specific expansion coefficients by exploiting the orthogonality of the eigenfunctions, analytically integrating over the piecewise initial configuration to arrive at the exact solution.
        </div>
        </details>
        </div>
        </div>
        </div>
        
        <hr style="opacity: 0.1; margin: 4rem 0;">

        <div class="expand-container">
        <div class="video-grid">
        <div class="video-wrapper">
        {{< youtube "8O5o263n6EM" >}}
        </div>
        <div>
        <h3 style="margin-top: 0;">Suspended Charges in Static Equilibrium | Transcendental Equation & Maclaurin Series</h3>
        <p><strong>Description:</strong><br>
        <em>A rigorous vector analysis of suspended charged particles, culminating in the analytical resolution of a transcendental equilibrium equation using small-angle approximations.</em></p>
        <details>
        <summary><span style="color:#3b82f6; cursor:pointer; font-weight:bold;">Read full description...</span></summary>
        <div style="margin-top: 10px; font-style: italic; font-size: 0.95rem;">
        In this lecture, we tackle a classic electrostatics problem: determining the equilibrium angle of two identical charged spheres suspended by strings. We begin with a rigorous free-body diagram and a vector application of Newton's Second Law, balancing tension, gravity, and the electrostatic Coulomb force. This analysis yields a nonlinear transcendental equation for the equilibrium angle $\theta$. To resolve this analytically, we justify the small-angle approximation by formally expanding the sine and cosine functions via their Maclaurin series. This mathematical technique reduces the complex system into a solvable algebraic equation, ultimately deriving the closed-form approximate solution for the system's configuration.
        </div>
        </details>
        </div>
        </div>
        </div>
        
        <hr style="opacity: 0.1; margin: 4rem 0;">
    
    design:
      spacing:
        padding: ['40px', '0', '80px', '0']
---
