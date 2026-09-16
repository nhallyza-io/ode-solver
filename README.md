# ODE Solver & Dynamical Systems

A Python repository dedicated to implementing numerical methods for solving Ordinary Differential Equations (ODEs) and modeling physical dynamical systems.

---

## Modules & Architecture

| Module | Focus Area & Numerical Schemes | Primary Scope |
| :--- | :--- | :--- |
| **`euler-methods/`** | Forward, Backward, and Modified Euler schemes | First-order numerical integration |
| **`runge-kutta/`** | Classic RK2, RK4, and adaptive step-size solvers (RK45) | Higher-order explicit solvers |
| **`verlet-integration/`** | Standard and Velocity Verlet algorithms | Symplectic schemes for Hamiltonian systems |
| **`boundary-value-probs/`** | Shooting methods and finite difference algorithms | Boundary value problem (BVP) solving |
| **`applications/`** | N-body celestial mechanics, oscillators, chaotic systems | Physical simulations and dynamic models |

---

## Tech Stack

* **Language:** Python 3.x
* **Core Libraries:** `NumPy`, `SciPy`, `Matplotlib`

---

## License

This project is licensed under the [MIT License](LICENSE).
