# European Options Pricing: Black-Scholes, Binomial Tree & Monte Carlo Simulation

This project implements and compares three fundamental models for pricing **European call and put options**:

- **Black-Scholes Analytical Model**
- **Binomial Tree Model**
- **Monte Carlo Simulation**

It is intended as a learning tool and practical reference for understanding the theory, implementation, and real-world application of option pricing and sensitivity analysis.

---

## 📌 Project Goals

- Implement the three standard models for European option pricing.
- Compare accuracy, performance, and assumptions.
- Visualize convergence behavior and parameter sensitivity.
- Calculate important risk metrics (Greeks) using both analytical and numerical methods.

---

## 💡 Models Implemented

| Model              | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| Black-Scholes      | Closed-form analytical solution under idealized assumptions.                |
| Binomial Tree       | Step-wise discrete model to simulate price paths and convergence behavior.  |
| Monte Carlo         | Simulates thousands of paths to estimate the expected payoff statistically. |

---

## 📈 Key Features

- ✅ Pricing of European call and put options
- ✅ Visualization of convergence (Binomial Tree)
- ✅ Comparison of models side by side
- ✅ Calculation of Greeks: Delta & Vega (using Black-Scholes & finite difference)
- ✅ Markdown cells discussing financial assumptions

---

## 📊 Greeks Calculated

| Greek | Description                        | Method Used            |
|-------|------------------------------------|------------------------|
| Delta | ∂Price/∂Spot Price                 | Black-Scholes & Finite Difference |
| Vega  | ∂Price/∂Volatility                 | Black-Scholes & Finite Difference |

---

## 🧠 Assumptions Discussed

- No arbitrage and frictionless markets
- Constant volatility and risk-free rate
- Lognormal distribution of asset prices
- Continuous time and trading
- European-style (exercisable only at expiry)

---

## 📎 Sample Output & Visualizations

- Line charts showing **Binomial Tree convergence** to Black-Scholes value
- Delta & Vega sensitivity calculations
- Markdown notes explaining assumptions and interpretation of results

---

## 🛠 Technologies Used

- Python (NumPy, Matplotlib, SciPy)
- Jupyter/Google Colab

---
