# The Quantum Wall Strategy: Modelling Financial Time Series using Bohmian Mechanics

![Language](https://img.shields.io/badge/Language-Python-blue.svg)
![Domain](https://img.shields.io/badge/Domain-Quant_Finance-green.svg)
![Methodology](https://img.shields.io/badge/Methodology-Econophysics-orange.svg)
![Status](https://img.shields.io/badge/Status-Research_Complete-red.svg)

## 📜 Abstract

This project details the development and execution of a novel financial modelling framework that fundamentally redefines market risk. [cite_start]Departing from the traditional "Random Walk" theory (Geometric Brownian Motion), this project treats the **NIFTY 50 stock index** as a physical particle traversing a "Quantum Potential Field." [cite: 5, 6]

[cite_start]By applying the mathematical formalism of **Bohmian Mechanics** (De Broglie-Bohm Pilot Wave Theory), we mapped the invisible forces of market psychology—Fear and Greed—into a calculable, predictive force field. [cite: 7]

## 🧠 Theoretical Framework

Modern finance relies on the Efficient Market Hypothesis, assuming returns follow a Normal Gaussian Distribution. [cite_start]However, the Indian market exhibits "Fat Tails" and "Long-Term Memory," contradicting these axioms. [cite: 14, 23, 24]

To model reality, we utilized Bohmian Mechanics, which suggests a particle is guided by an invisible "Pilot Wave." In this model:
* [cite_start]**The Particle:** The observable Spot Price ($P_t$). [cite: 32]
* [cite_start]**The Pilot Wave ($\psi$):** The collective market psychology (Probability Density). [cite: 33, 34]
* [cite_start]**The Quantum Potential ($Q$):** The "Information" field guiding the price. [cite: 36]

### The Governing Equation
The core of the model relies on the Quantum Potential ($Q$), derived from the Schrödinger equation:

$$Q = -\frac{\hbar^{2}}{2m} \frac{\nabla^{2}R}{R}$$

Where:
* [cite_start]$R$ is the amplitude of the wave function ($\sqrt{P}$). [cite: 43]
* [cite_start]$\nabla^{2}$ is the curvature of the probability field. [cite: 44]
* [cite_start]$m$ is the "Mass" of the market (derived from Trading Volume). [cite: 46]

## 📊 Methodology

### Data Source
* **Asset:** NIFTY 50 Index.
* [cite_start]**Timeline:** January 1, 2020 – October 2025 (covering COVID-19 crash, Bull Run, and Consolidation). [cite: 58]
* [cite_start]**Transformation:** Raw prices converted to **Logarithmic Returns** to ensure time additivity and symmetry. [cite: 69]

### The Physics Engine
[cite_start]We estimated the Probability Density ($P$) using **Gaussian Kernel Density Estimation (KDE)** with Scott's Rule for dynamic bandwidth selection. [cite: 77] This allowed us to calculate the Quantum Potential ($Q$) and identify:
1.  [cite_start]**Valleys:** Areas of stability where price wanders freely. [cite: 50]
2.  [cite_start]**Quantum Walls:** Price barriers where probability collapses ($Q$ spikes), creating a repulsive force. [cite: 52, 54]

## 🧪 Key Discoveries & Validation

Before trading, we performed rigorous Econophysics testing to validate the model:

### 1. The "Black Swan" Proof (Kurtosis)
* [cite_start]**Result:** NIFTY 50 Kurtosis = **22.76** (Normal distribution = 3). [cite: 86]
* [cite_start]**Implication:** The market has massive "Fat Tails," validating the existence of deep Potential Wells. [cite: 87, 91]

### 2. The "Memory" Proof (Hurst Exponent)
* [cite_start]**Result:** $H$ = **0.3872**. [cite: 94]
* **Implication:** The market is **Anti-Persistent** (Mean Reverting). [cite_start]It fights the trend, acting like a rubber band. [cite: 94, 97]

### 3. The Law of Asymmetric Instability
By mapping the 2D Joint Quantum Potential ($Q(R,V)$), we discovered that maximum systemic risk does **not** occur at peak volume.

> **Discovery:** The point of maximum instability occurs at a **Liquidity Vacuum** (Volume = 0.38). [cite: 121]

[cite_start]Unlike the "Panic Selling" theory (high volume), the most dangerous crashes occur when volume dries up, creating an "Air Pocket." [cite: 121] [cite_start]The force vector analysis at this point ($179.82^{\circ}$) proves the market forces a V-shaped price recovery regardless of volume participation. [cite: 125, 128]

## 📈 Trading Strategy Performance

We engineered an algorithm that utilizes "Quantum Walls" as bifurcation points.

* **Logic:**
    * [cite_start]**Breakout Up:** If Price > Upper Wall $\rightarrow$ **BUY** (Momentum). [cite: 148]
    * [cite_start]**Breakout Down:** If Price < Lower Wall $\rightarrow$ **SELL** (Short). [cite: 149]

| Metric | Value |
| :--- | :--- |
| **Strategy ROI** | [cite_start]**77.9%** (Absolute Return) [cite: 156] |
| **Market ROI** | [cite_start]115.0% (Buy & Hold) [cite: 157] |
| **Wall Breakout Rate** | [cite_start]**56.64%** [cite: 159] |
| **Wall Bounce Rate** | [cite_start]43.36% [cite: 158] |

**Performance Note:** While the absolute ROI is lower than Buy & Hold, the strategy provided superior risk management. [cite_start]During the COVID-19 crash (where B&H lost ~40%), this strategy signaled a **Short**, protecting capital. [cite: 161, 162]

## 🚀 Future Scope

1.  [cite_start]**Algorithmic Scalping:** Using Force Vector direction for HFT. [cite: 174]
2.  [cite_start]**Q-VIX (Quantum Volatility Index):** Using "Rolling Wall Width" as a predictive alternative to VIX. [cite: 175]
3.  [cite_start]**Tail-Risk Hedging:** Pricing Put Options based on true Potential Depth rather than Black-Scholes. [cite: 177]

## 📝 Author

> **Mashhood Raza Khan** 
*3rd Year BSc Economics Honours Student*

---
*Disclaimer: This project is for educational and research purposes only. It does not constitute financial advice.*
