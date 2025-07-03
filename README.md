# Nonlinear Coupled Flow Heat Transfer Problem

A comprehensive Computational Fluid Dynamics (CFD) simulation project implementing finite element method (FEM) for heat transfer and Navier-Stokes equations with advanced numerical methods and adaptive mesh refinement.

## Description

This project implements numerical simulations for coupled heat transfer and fluid flow problems using the finite element method. The simulation framework supports both thermal analysis and incompressible flow calculations with the SUPG (Streamline-Upwind Petrov-Galerkin) stabilization technique.

The solver handles:
- **Heat Transfer Problems** - thermal conduction, convection, and radiation
- **Fluid Flow Problems** - incompressible Navier-Stokes equations
- **Coupled Simulations** - simultaneous heat and mass transfer
- **Adaptive Mesh Refinement** - automatic grid optimization
- **Multiple Linear Solvers** - direct, iterative, and multigrid methods

Key numerical features include time integration schemes, boundary condition enforcement, and convergence monitoring with comprehensive output capabilities.

## Features

### 🔥 **Heat Transfer Simulation**
- **Thermal Conduction** - steady-state and transient heat transfer
- **Boundary Conditions** - isothermal, heat flux, convection/radiation
- **Material Properties** - temperature-dependent thermal conductivity
- **Time Integration** - implicit Euler and Crank-Nicolson schemes

### 🌊 **Fluid Flow Simulation**
- **Navier-Stokes Equations** - incompressible flow solver
- **SUPG Stabilization** - streamline-upwind Petrov-Galerkin method
- **Boundary Conditions** - no-slip walls, inflow/outflow, symmetry
- **Reynolds Number Effects** - configurable viscosity and flow parameters

### 🔧 **Numerical Methods**
- **Finite Element Method** - triangular/tetrahedral elements
- **Adaptive Mesh Refinement** - Zienkiewicz-Zhu error estimation
- **Multiple Linear Solvers** - direct, GMRES, multigrid
- **Time Stepping** - adaptive time step control

### 📊 **Simulation Control**
- **Convergence Monitoring** - nonlinear and linear solver tracking
- **Error Estimation** - multiple error norms and tolerance settings
- **Data Output** - regular dumps for visualization and restart
- **Parameter Sweeps** - configurable simulation parameters

### 🎨 **Visualization Support**
- **Temperature Evolution** - animated temperature fields (`change_in_temperature.avi`)
- **Flow Visualization** - velocity and pressure fields
- **Mesh Visualization** - adaptive grid display
- **Convergence Plots** - error and residual tracking

