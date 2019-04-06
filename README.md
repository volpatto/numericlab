# NumericLab

A repo for training and learning numerical methods with C++ ([Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page) and [xtensor](http://quantstack.net/xtensor.html)). Here, I provide a numerical stack in Modern C++,
trying to follow C++11 standard or above. For `xtensor`, it must be necessarily C++14 or above.

__This repo will be always under development!__ But I must emphasize that I will contribute here only __in my free time.__

## Purpose

Training. Exercising. And a Rough Suffering. TEARS, for short.

More clearly: the main purpose of this repo is learning. I want to improve my C++ skills and consolidate a minimal C++ stack for scientific/numerical developers. I am learning while I do the implementations. Do not expect optimal codes here, best pratices and things like that. I am not (too much) concerned about this point, but I will try to do a minimal effort for it.

## Planning

The planned contents are:

* Minimal C++ background (prerequistes). As we use `Eigen` and `xtensor`, it means essentially Templates. A brief language overview and important features for the numerical applications will be provided.

* Simple numerical methods. Very basic methods from this discipline, just for practicing. All the methods will be implemented using `Eigen` and `xtensor`, a version for each lib. The following methods are planned:

  1. Root-finding methods:
      - Bisection;
      - Secant method (quasi Newton);
      - Newton.
  2. Linear systems solvers:
      - Jacobi;
      - Gauss-Seidel;
      - SOR.
  3. Interpolation:
      - Lagrange polynomials.
  4. Numerical quadrature:
      - Open Newton-Cotes formula;
      - Closed Newton-Cotes formula;
      - Gauss-Legendre Quadrature example.
  5. ODE solvers:
      - Explicit Euler;
      - Implicit Euler;
      - Crank-Nicolson;
      - Explicit Runge-Kutta 4th order.
  6. 1D PDE solvers:
      - Finite Difference Method (FDM) for Poisson problem;
      - FDM for Parabolic (transient) problem.
      
Finally, but important: __maybe this repo is just another project I created which will be not continued__. Maybe not.

## About me

My name is Diego. Just a developer under development. Occasionally a doctoral student.

* email: dtvolpatto@gmail.com
