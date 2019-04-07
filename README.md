# NumericLab

A repo for training and learning numerical methods with C++ ([Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page) and [xtensor](http://quantstack.net/xtensor.html)). Here, I provide a numerical stack in Modern C++,
trying to follow C++11 standard or above. For `xtensor`, it must be necessarily C++14 or above.

__This repo will be always under development!__ But I must emphasize that I will contribute here only __in my free time.__

## Purpose

Training. Exercising. And a Rough Suffering. TEARS, for short.

More clearly: the main purpose of this repo is learning. I want to improve my C++ skills and consolidate a minimal C++ stack for scientific/numerical developers. I am learning while I do the implementations. Do not expect optimal codes here, best practices and things like that. I am not (too much) concerned about this point, but I will try to do a minimal effort for it.

## Planning

The planned contents are:

* Minimal C++ background (prerequistes). As I'm using `Eigen` and `xtensor`, it means essentially Templates. A brief language overview and important features for the numerical applications will be provided. Most of such stuffs will be available in `jupyter notebook`s using [xeus](http://quantstack.net/xeus) to enable the C++ kernel.

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

## Usage

If you, by chance, find any usage in any available code, feel free to use. But I do not guarantee nothing.

To run anything from this repo, a proper [conda](https://conda.io/en/latest/) environment is needed (although you can install and build the dependencies by yourself as well). To reproduce the same environment I use, just create an environment from the file `cpp-stack-env.yml`.

## Implementation check-list

* xtensor:

  1. Root-finding methods:
      - [ ] Bisection;
      - [ ] Secant method (quasi Newton);
      - [ ] Newton.
  2. Linear systems solvers:
      - [ ] Jacobi;
      - [ ] Gauss-Seidel;
      - [ ] SOR.
  3. Interpolation:
      - [ ] Lagrange polynomials.
  4. Numerical quadrature:
      - [ ] Open Newton-Cotes formula;
      - [ ] Closed Newton-Cotes formula;
      - [ ] Gauss-Legendre Quadrature example.
  5. ODE solvers:
      - [ ] Explicit Euler;
      - [ ] Implicit Euler;
      - [ ] Crank-Nicolson;
      - [ ] Explicit Runge-Kutta 4th order.
  6. 1D PDE solvers:
      - [ ] Finite Difference Method (FDM) for Poisson problem;
      - [ ] FDM for Parabolic (transient) problem.
      
* Eigen:

  1. Root-finding methods:
      - [ ] Bisection;
      - [ ] Secant method (quasi Newton);
      - [ ] Newton.
  2. Linear systems solvers:
      - [ ] Jacobi;
      - [ ] Gauss-Seidel;
      - [ ] SOR.
  3. Interpolation:
      - [ ] Lagrange polynomials.
  4. Numerical quadrature:
      - [ ] Open Newton-Cotes formula;
      - [ ] Closed Newton-Cotes formula;
      - [ ] Gauss-Legendre Quadrature example.
  5. ODE solvers:
      - [ ] Explicit Euler;
      - [ ] Implicit Euler;
      - [ ] Crank-Nicolson;
      - [ ] Explicit Runge-Kutta 4th order.
  6. 1D PDE solvers:
      - [ ] Finite Difference Method (FDM) for Poisson problem;
      - [ ] FDM for Parabolic (transient) problem.

## About me

My name is Diego. Just a developer under development. Occasionally a doctoral student.

* email: dtvolpatto@gmail.com
