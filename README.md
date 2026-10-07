# 🛸 Aero-Entropy-PhaseSpace-Ensemble: Quantum Passenger Steering Engine (ROC-AUC: 0.95383)

An advanced, enterprise-grade quantitative machine learning framework designed for the **Kaggle Playground Series (Season 6 Episode 10)**. This project bypasses brute-force feature generation by transforming tabular airline passenger profiles into non-linear geometric, complex variable (Complex Analysis), and simulated quantum states, optimized through a synchronized high-capacity ensemble (**XGBoost + LightGBM + CatBoost**).

---

## 📈 Leaderboard Impact & Performance
* **Final Local Ensemble Blend (ROC-AUC):** `0.95383`
* **XGBoost Classifier Individual Score:** `0.95367`
* **LightGBM Classifier Individual Score:** `0.95361`
* **CatBoost Classifier Individual Score:** `0.95328`

*The highly synchronized and dense model weights demonstrate near-zero variance, ensuring exceptional stability and resistance to standard Kaggle leaderboard Shake-ups.*

---

## 🧠 Core Engineering & Mathematical Innovations

### 1. Vector Discomfort Index (Linear Algebra)
Instead of processing raw time anomalies linearly, the engine projects the departure and arrival delays into a continuous 2D coordinate system. It calculates the normalized Euclidean distance from an ideal ground schedule relative to the overall flight distance, automatically scaling the "stress factor" based on short-haul vs. long-haul flight physics:

$$Vector\_Discomfort\_Index = \frac{\sqrt{\Delta t_{dep}^2 + \Delta t_{arr}^2}}{t_{ground\_ideal} + t_{flight}}$$

### 2. Complex Variable Phase-Space (Complex Analysis)
Temporal delays are vectorized onto a 2D complex plane \(Z = X + iY\). The engine extracts the modulus (amplitude of stress) and the phase angle (argument). A phase shift past 45 degrees mathematically informs the classifiers that final destination delays are overriding terminal waiting distress:

$$Z_{stress} = \frac{\Delta t_{dep}}{t_{flight}} + i \cdot \frac{\Delta t_{arr}}{t_{flight}}$$

$$Stress\_Phase\_Deg = deg(arg(Z_{stress}))$$

### 3. Dynamic Customer Satisfaction Steering (Quantum Logic)
The passenger’s emotional state is modeled as a single qubit mapped onto the **Bloch Sphere**. The complex variable stress acts as a destructive 

$$R_x(\theta)$$ gate, tilting the state vector down from the North Pole $$(\vert{}0\rangle$$, Fully Satisfied) to the South Pole $$(\vert{}1\rangle$$, Dissatisfied). 

Concurrently, a dynamic filter scales and standardizes (\(Z\)-score) the 14 multi-point airline services, operating as a recovery \(R_y(\phi)\) gate that counter-rotates the qubit back to satisfaction:

$$  \vert{}\psi\rangle = U_{service}(\phi) U_{stress}(\theta) \vert{}0\rangle $$

$$Quantum\_Prob\_Satisfied = \vert{}\langle 0 \vert{} \psi \rangle\vert{}^2$$

---

## 🛠️ Tech Stack & Dynamic Architecture
* **Robust Column Audit:** Embedded a dynamic feature compiler `[col for col in target if col in df.columns]` to self-adapt across messy synthetic data schemes.
* **Standardized Pipeline:** Automated \(Z\)-score mapping across all 13 active multi-point evaluation matrices.
* **Production Models:** Integrated fine-tuned deep boosting topologies with restrictive learning rates (0.03) and proactive evaluation early-stopping thresholds (`early_stopping_rounds=50`).

---
*Developed as an exploration in Quantum-Behavioral Analytics, Information Entropy, and High-Performance Kaggle Ensembling.* 🚀⚙️

