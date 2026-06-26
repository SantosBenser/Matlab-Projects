# Simulation and Statistical Verification of Bivariate Gaussian Random Vectors using Cholesky Decomposition (Stock Price & Market Index Model)

## 📌 Title

Simulation and Statistical Verification of Bivariate Gaussian Random Vectors using Cholesky Decomposition (Stock Price & Market Index Model)

A MATLAB-based statistical simulation project that models the relationship between stock prices and market indices using a bivariate Gaussian distribution. The project employs Cholesky decomposition to generate correlated random variables and statistically verifies that the simulated data follows the desired theoretical distribution.

---

## 🛠 Technologies

### Programming Language
- MATLAB

### MATLAB Functions & Tools
- `randn()`
- `chol()`
- `mean()`
- `cov()`
- `scatter()`
- Matrix Operations
- Statistical Analysis Toolbox

### Concepts
- Probability Theory
- Random Processes
- Bivariate Gaussian Distribution
- Cholesky Decomposition
- Correlated Random Variables
- Covariance Matrix
- Statistical Verification
- Financial Modeling
- Monte Carlo Simulation

---

## ✨ Features

- Simulation of correlated Gaussian random variables
- Implementation of Cholesky decomposition
- Modeling of stock-market relationships
- Generation of large-scale random samples
- Scatter plot visualization of simulated data
- Empirical mean verification
- Empirical covariance verification
- Comparison with theoretical statistics
- Financial interpretation of correlated data
- Statistical validation of generated samples

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Function |
|----------|----------|
| Ctrl + N | Create New Script |
| Ctrl + O | Open Script |
| Ctrl + S | Save Script |
| F5 | Run MATLAB Script |
| Ctrl + R | Comment Selected Lines |
| Ctrl + T | Uncomment Selected Lines |
| Ctrl + C | Stop Execution |
| Ctrl + Z | Undo |
| Ctrl + Shift + S | Save As |

---

## ⚙️ The Process

### 1. Define Statistical Parameters

The simulation begins by defining:

- Mean vector

```text
μ = [1, 2]
```

- Covariance matrix

```text
Σ = [1   0.8
     0.8 2]
```

The covariance value of **0.8** indicates a strong positive relationship between the stock price and the market index. :contentReference[oaicite:2]{index=2}

---

### 2. Generate Independent Gaussian Variables

Standard normally distributed random variables are generated using MATLAB's random number functions.

These variables initially have:

- Zero mean
- Unit variance
- No correlation

---

### 3. Perform Cholesky Decomposition

The covariance matrix is decomposed using:

```text
Σ = LLᵀ
```

where:

- **L** is a lower triangular matrix.

Cholesky decomposition introduces the required correlation structure into the random samples. :contentReference[oaicite:3]{index=3}

---

### 4. Generate Correlated Samples

The independent Gaussian samples are multiplied by the Cholesky matrix to obtain correlated random vectors representing:

- Market index fluctuations
- Stock price behavior

---

### 5. Visualize the Data

A scatter plot is generated to observe the relationship between the two variables.

The simulated points exhibit:

- Upward trend
- Positive correlation

showing that stock prices increase as market indices increase. :contentReference[oaicite:4]{index=4}

---

### 6. Statistical Verification

The generated data is statistically verified by computing:

#### Empirical Mean

```text
Empirical Mean ≈ [1, 2]
```

#### Empirical Covariance Matrix

The empirical covariance matrix closely matches the theoretical covariance matrix:

```text
[1   0.8
 0.8 2]
```

This confirms that the generated samples follow the desired bivariate Gaussian distribution. :contentReference[oaicite:5]{index=5}

---

## 📚 What I Learned

- MATLAB programming
- Random process simulation
- Bivariate Gaussian distributions
- Cholesky decomposition
- Covariance and correlation concepts
- Statistical verification techniques
- Financial system modeling
- Monte Carlo methods
- Matrix computations
- Data visualization in MATLAB

---

## 📈 Overall Growth

This project provided practical experience in applying probability theory and statistical techniques to real-world financial systems. I gained a deeper understanding of correlated random variables, covariance structures, and matrix decomposition methods.

The project strengthened my skills in MATLAB programming, statistical analysis, simulation modeling, and interpreting financial relationships using mathematical tools.

---

## 🚀 How Can It Be Improved

- Extend to multivariate Gaussian models
- Simulate multiple stock portfolios
- Include time-varying covariance models
- Implement Monte Carlo risk estimation
- Add Value-at-Risk (VaR) analysis
- Develop portfolio optimization techniques
- Integrate real stock market datasets
- Build an interactive MATLAB GUI
- Compare Cholesky with other decomposition methods
- Implement machine learning-based forecasting

---

## ▶️ Running the Project

### Requirements

- MATLAB R2020a or later

### Steps

1. Open MATLAB.
2. Create a new script.
3. Copy and paste the MATLAB code.
4. Save the file as:

```text
bivariate_gaussian_simulation.m
```

5. Run the script by pressing:

```text
F5
```

### Expected Output

The program generates:

- Correlated random samples
- Scatter plot visualization
- Empirical mean values
- Empirical covariance matrix

The scatter plot should show a clear positive correlation between stock price and market index. :contentReference[oaicite:6]{index=6}

---

## 📊 Statistical Verification

### Theoretical Mean

```text
[1, 2]
```

### Empirical Mean

```text
Approximately [1, 2]
```

### Theoretical Covariance Matrix

```text
[1   0.8
 0.8 2]
```

### Empirical Covariance Matrix

```text
Approximately equal to theoretical covariance matrix
```

Successful verification confirms the correctness of the simulation. :contentReference[oaicite:7]{index=7}

---

## 💹 Real-World Interpretation

The model represents:

- Market index fluctuations (economic conditions)
- Stock price reactions (company performance + market influence)

A positive covariance value of **0.8** indicates that the stock is strongly influenced by overall market conditions. :contentReference[oaicite:8]{index=8}

---

## 🎯 Applications

- Stock Market Prediction
- Portfolio Risk Analysis
- Financial Modeling
- Algorithmic Trading
- Risk Management Systems
- Monte Carlo Simulations
- AI in Finance
- Quantitative Finance Research

---

## 👨‍💻 Author

**Santos**

---

*"Transforming mathematical theory into practical financial simulations through statistical modeling."*
