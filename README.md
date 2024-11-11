# Optimization_Algorithms
Optimization Algorithms Comparison Project

*Project Overview :*

This project implements and compares different optimization algorithms, including Gradient Descent (fixed and optimal step size), Conjugate Gradient (linear and nonlinear), and Spectral Gradient methods (BB1 and BB2). Each method is applied to a variety of test functions, allowing for performance evaluation based on convergence speed, accuracy, and robustness.

The analysis is structured as a series of TPs (Travaux Pratiques) to explore and understand these algorithms' practical applications in solving optimization problems.

*Project Structure :*
  
  - TP1: Gradient Descent
    
      - Gradient Descent with Fixed and Optimal Step Sizes: Implements two variants of the gradient descent method.
      - Test Functions: Utilizes several test functions (J1, J2, JR) and their gradients.
      - Validation Tests: Conducts tests to ensure correctness of the gradient descent implementation.
      - Parabolic Approximation Construction: Approximates the functions to analyze convergence behavior.
      - Application on Jh: Evaluates the performance of the descent methods on a specific test function Jh.
  
  - TP2: Conjugate Gradient Method

      - Linear Conjugate Gradient: Implements the classical linear conjugate gradient algorithm.
      - Minimization of J3 and J4: Applies the conjugate gradient method to test functions J3 and J4.
      - Nonlinear Conjugate Gradient: Uses the Fletcher-Reeves method for nonlinear conjugate gradient, applied to test function Jeps.

  - TP3: Spectral Gradient Method

      - Spectral Gradient Algorithms (BB1 and BB2): Implements the BB1 and BB2 variants of the spectral gradient method.
      - Validation Tests on J1 and J2: Validates the spectral gradient methods on basic functions.
      - Application on Complex Functions (J5, J6, and JR): Analyzes the convergence behavior on more complex test functions.
      - Comparison Across Methods: Compares the nonlinear conjugate gradient (NLGC), BB1, and BB2 on functions Jh and JR to identify the most efficient method.


*Key Features :*

  - Algorithm Comparison: Compares multiple optimization techniques for efficiency and accuracy.
  - Function Minimization: Demonstrates methods on a variety of test functions, from simple quadratic functions to more complex structures like the Rosenbrock function.
  - Convergence Analysis: Plots and compares convergence rates of different algorithms.
