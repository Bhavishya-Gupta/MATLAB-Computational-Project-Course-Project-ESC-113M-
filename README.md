

# MATLAB Computational Project (ESC-113M)

<p align="center">
  <img src="https://img.shields.io/badge/MATLAB-F9931E?style=for-the-badge&logo=mathworks&logoColor=white" alt="MATLAB"/>
  <img src="https://img.shields.io/badge/Computational%20Methods-0076A8?style=for-the-badge" alt="Computational Methods"/>
  <img src="https://img.shields.io/badge/Course-ESC%20113M-blue?style=for-the-badge" alt="Course"/>
  <img src="https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge" alt="Status"/>
</p>
<p align="center">
  <strong>A comprehensive computational methods project for engineers, featuring problem statements, MATLAB solution codes, and a detailed final report on engineering analyses and numerical methods.</strong>
</p>

***

## 🎯 Project Overview

### **Course Context**

ESC-113M: *Computer Methods for Engineers*
Semester Project focusing on implementing numerical algorithms for engineering applications using MATLAB.

### **Objectives**

- Apply numerical techniques (finite difference, integration, ODE solvers) to real-world engineering problems
- Develop modular, well-documented MATLAB code for computational analysis
- Validate results through comparison with analytical or experimental data
- Compile findings into a professional final report

***

## 📁 Repository Structure

```
MATLAB-Computational-Project-ESC-113M/
│
├── 📄 Problem Statements/
│   ├── Problem1_HeatEquation.pdf
│   ├── Problem2_NumericalIntegration.pdf
│   └── Problem3_ODE_Simulation.pdf
│
├── 📂 MATLAB_Code/
│   ├── heat_equation_fdm.m
│   ├── trapezoidal_integration.m
│   ├── ode_solver_runge_kutta.m
│   ├── main_script.m
│   └── utils/
│       ├── boundary_conditions.m
│       └── plot_results.m
│
├── 📑 Final_Report.pdf
├── 📄 README.md          # Original documentation
└── 📄 LICENSE
```


***

## 🔬 Engineering Problems \& Numerical Methods

| Problem | Numerical Method | MATLAB Implementation |
| :-- | :-- | :-- |
| **1** | 1D Heat Equation (Finite Difference Method) | `heat_equation_fdm.m` |
| **2** | Definite Integrals (Composite Trapezoidal Rule) | `trapezoidal_integration.m` |
| **3** | Ordinary Differential Equations (4th-order Runge–Kutta) | `ode_solver_runge_kutta.m` |


***

## 🛠️ MATLAB Code Highlights

### **1. Finite Difference for Heat Equation**

- Discretizes spatial domain into uniform grid
- Explicit time stepping with stability analysis
- Modular boundary condition handling
- Plots temperature profile evolution


### **2. Composite Trapezoidal Integration**

- Generic function accepts any continuous integrand
- Adaptive partition refinement for error control
- Comparison with MATLAB’s built-in `integral` function


### **3. Runge–Kutta ODE Solver**

- Implements 4th-order Runge–Kutta method
- Solves non-linear dynamic systems
- Includes event detection for stopping criteria

***

## 📊 Final Report Summary

- **Introduction**: Overview of numerical methods and engineering applications
- **Methodology**: Derivation of finite difference scheme, integration error analysis, and RK4 algorithm
- **Results**:
    - Temperature diffusion profiles
    - Numerical integration error vs. analytical values
    - ODE simulation trajectories
- **Validation**: Comparison plots demonstrating <1% error in all cases
- **Discussion**: Stability criteria, convergence rates, and computational performance
- **Conclusions**: Best practices for choosing step sizes and methods for various problem classes
- **Appendices**: MATLAB code listings and user manual

***

## 🚀 Getting Started

### **Prerequisites**

- MATLAB R2020a or later
- Control System \& PDE toolboxes (for visualization)


### **Setup \& Execution**

1. Clone the repository

```bash
git clone https://github.com/Bhavishya-Gupta/MATLAB-Computational-Project-Course-Project-ESC-113M-.git
cd MATLAB-Computational-Project-ESC-113M-
```

2. Open MATLAB and set path to project folder
3. Run `main_script.m` to execute all problems and generate figures
4. Review `Final_Report.pdf` for detailed analysis

***

## 📚 Educational Impact

- Demonstrates core computational methods essential for engineering
- Provides a template for modular code development and documentation
- Bridges theoretical derivations with practical MATLAB implementations
- Serves as a reference for future numerical analysis projects

***

## 🤝 Collaboration \& Attribution

### **Author**

**Bhavishya Gupta**

- GitHub: [@Bhavishya-Gupta](https://github.com/Bhavishya-Gupta)
- Email: Available upon request
- Specialization: Numerical methods, computational engineering


### **License**

This project is released under the MIT License. See [LICENSE](LICENSE) for details.

<p align="center">
  <strong>⭐ If this project enhances your understanding of computational methods, please consider giving it a star! ⭐</strong>
</p>
<p align="center">
  <em>“Transforming engineering problems into computational solutions with MATLAB.”</em>
</p>
<p align="center">
  <strong>🔢 ESC-113M: Computational Methods for Engineers 🔢</strong>
</p>


[^1]: https://github.com/Bhavishya-Gupta/MATLAB-Computational-Project-Course-Project-ESC-113M-

