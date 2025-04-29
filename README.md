# Semiconductor-Production-Line-Downtime-Analysis-Using-Markov-Models-and-Q-Learning
---

## Project Overview

This project presents a data-driven approach to optimizing maintenance strategies in semiconductor production lines. Using **Markov Models**, **Markov Decision Processes (MDP)**, **Q-Learning**, and **Monte Carlo Simulations**, the project identifies and validates optimal policies for minimizing downtime, reducing defect rates, and improving operational cost efficiency.

---

## Objectives

- Model equipment state transitions using Markov Chains.
- Analyze the impact of downtime on semiconductor wafer yield.
- Optimize inspection, repair, and rework decisions using Q-Learning.
- Validate model robustness through large-scale Monte Carlo simulations.

---

## Project Structure

| Section                         | Description |
|----------------------------------|-------------|
| Introduction                    | Problem context and motivation |
| Objective                       | Clear project goals |
| States (S0 to S4)                | Definition of equipment states |
| Assumptions                     | Modeling assumptions |
| Methodology                     | Data collection, model building, validation |
| Key Concepts Used               | Markov Chains, MDP, Q-Learning, Monte Carlo |
| Actions and Cost-Reward Analysis | Action set and their associated rewards/costs |
| MDP Optimization – Q-Learning   | Training process and Bellman update |
| Optimal Maintenance Policy      | Final learned maintenance strategy |
| Validation Results (Monte Carlo)| Simulation outcomes and performance metrics |
| Future Applications             | Industrial extensions and research opportunities |
| Conclusion                      | Summary of findings |

---

## Key Features

- **Markov Chain modeling** of machine operational dynamics.
- **Q-Learning optimization** to derive proactive maintenance strategies.
- **Dynamic Transition Probability Adjustment** simulating machine degradation over time.
- **Monte Carlo simulation** for robust validation across 10,000+ scenarios.
- **Performance Metrics:** Success Rate, MTBF, MTTR, Maintenance Costs.

---


4. View generated plots:
   - Reward Convergence
   - Monte Carlo Distributions (Rewards, MTBF, MTTR, Costs)

---

## 📊 Example Results

| Metric                         | Value         |
|---------------------------------|---------------|
| Average Reward per Episode      | ~245.85       |
| Success Rate                    | ~97.81%       |
| Estimated MTBF (Steps)           | ~26.49        |
| Estimated MTBR (Steps)           | ~25.39        |
| Average Maintenance Cost/Episode| ~$16.98       |

---

## 🌍 Future Applications

- Smart predictive maintenance scheduling in semiconductor fabs.
- Integration with real-time IoT and Digital Twin systems.
- Application to aerospace, healthcare equipment, and smart manufacturing.
- Development of autonomous maintenance decision-making platforms aligned with Industry 4.0 initiatives.

---

## By

- **Abhijeet Verma** – Arizona State University  

Instructor: **Dr. Giulia Pedrielli**  
Course: **IEE 575: Applied Stochastic Operations Research Models**  
Institution: **Arizona State University (ASU)**

---


