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

SS\[\text{Vector\_Discomfort\_Index} = \frac{\sqrt{\Delta t_{\text{dep}}^2 + \Delta t_{\text{arr}}^2}}{t_{\text{ground\_ideal}} + t_{\text{flight}}}\]SS

### 2. Complex Variable Phase-Space (Complex Analysis / TFFP)
Temporal delays are vectorized onto a 2D complex plane (\(Z = X + iY\)). The engine extracts the modulus (amplitude of stress) and the phase angle (argument). A phase shift past \(45^\circ\) mathematically informs the classifiers that final destination delays are overriding terminal waiting distress:

\[Z_{\text{stress}} = \frac{\Delta t_{\text{dep}}}{t_{\text{flight}}} + i \cdot \frac{\Delta t_{\text{arr}}}{t_{\text{flight}}}\]
\[\text{Stress\_Phase\_Deg} = \text{deg}(\arg(Z_{\text{stress}}))\]

### 3. Dynamic Customer Satisfaction Steering (Quantum Logic)
The passenger’s emotional state is modeled as a single qubit mapped onto the **Bloch Sphere**. The complex variable stress acts as a destructive \(R_x(\theta)\) gate, tilting the state vector down from the North Pole (\(\vert{}0\rangle\), Fully Satisfied) to the South Pole (\(\vert{}1\rangle\), Dissatisfied). 

Concurrently, a dynamic filter scales and standardizes (\(Z\text{-score}\)) the 14 multi-point airline services, operating as a recovery \$R_y\((\phi)\)\( gate that counter-rotates the qubit back to satisfaction:  \)\$

\(\vert{}\psi\rangle = U_{\text{service}}(\phi) U_{\text{stress}}(\theta) \vert{}0\rangle\)
\[ \]
\(\text{Quantum\_Prob\_Satisfied} = \vert{}\langle 0 \vert{} \psi \rangle\vert{}^2\)

