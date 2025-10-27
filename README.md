# Hybrid Option Pricing with Physics-Informed Neural Networks (PINNs)

The classical **Black–Scholes option pricing model** reaches its empirical limits due to restrictive assumptions, while purely data-driven **deep learning models** often suffer from poor generalization and lack of theoretical grounding.  
This project addresses this gap by developing and evaluating a **hybrid approach** for pricing European options: **Physics-Informed Neural Networks (PINNs)** with **Black–Scholes regularization**.

## Overview
The model integrates the **Black–Scholes partial differential equation (PDE)** as a **regularization term** in the neural network’s loss function.  
Training and testing are performed on a large dataset of **S&P 500 index options** from **2019 to 2024**, with separate analyses for call and put options.

## Key Results
- The **PINN-based model** significantly outperforms the classical Black–Scholes model.  
- The hybrid approach reduces pricing errors by **several orders of magnitude**.  
- Systematic biases such as the **volatility smile** are effectively eliminated.  
- In **data-sparse regions** of the option space, the PDE regularization ensures **robust and stable price predictions**, where traditional models fail.

## Conclusion
This work demonstrates that combining **financial theory** with **data-driven flexibility** leads to more **accurate, robust, and realistic** valuation models for financial derivatives.
