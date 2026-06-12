# PokerAI
# ♠️ Project Chimera

### Multi-Agent Poker Intelligence Engine

> A research-grade AI platform for Texas Hold'em Poker combining Game Theory, Reinforcement Learning, Monte Carlo Search, Opponent Modeling, and Explainable AI.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![NextJS](https://img.shields.io/badge/Next.js-Frontend-black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)

---

## Overview

Project Chimera is a next-generation Poker AI research platform designed to explore strategic decision-making in imperfect-information environments.

The system combines:

* Counterfactual Regret Minimization (CFR)
* Monte Carlo Tree Search (MCTS)
* Deep Reinforcement Learning
* Opponent Modeling
* Explainable AI

to create intelligent poker agents capable of competing against humans and other AI systems.

Unlike traditional poker simulators, Project Chimera focuses on strategic reasoning, equilibrium approximation, adaptive behavior, and interpretable decision intelligence.

---

## Why This Project?

Poker represents one of the most challenging environments in Artificial Intelligence because it contains:

* Hidden Information
* Uncertainty
* Long-Term Planning
* Multi-Agent Interaction
* Adversarial Decision Making

The same principles are used in:

* Quantitative Trading
* Autonomous Negotiation Systems
* Strategic Resource Allocation
* Algorithmic Market Making
* Multi-Agent Reinforcement Learning

Project Chimera serves as a research platform for studying these complex decision-making systems.

---

# Key Features

## Multi-Agent Poker Framework

Supports multiple AI agents:

* CFR Agent
* CFR+ Agent
* Monte Carlo CFR Agent
* MCTS Agent
* PPO Agent
* DQN Agent
* Rule-Based Agent
* Random Baseline Agent

Run:

* AI vs AI
* Human vs AI
* Tournament Mode
* Self-Play Training

---

## Counterfactual Regret Minimization

Implemented algorithms:

* Vanilla CFR
* CFR+
* Monte Carlo CFR

Capabilities:

* Regret Tracking
* Strategy Convergence
* Exploitability Analysis
* Nash Approximation

Visualize how equilibrium strategies emerge over time.

---

## Monte Carlo Tree Search

Complete implementation of:

1. Selection
2. Expansion
3. Simulation
4. Backpropagation

Features:

* Search Tree Visualization
* Visit Counts
* Expected Value Analysis
* Decision Path Inspection

---

## Deep Reinforcement Learning

Supported algorithms:

* PPO
* DQN
* A2C

Training Features:

* Self Play
* Experience Replay
* Model Checkpointing
* Distributed Training
* Hyperparameter Optimization

Analytics:

* Reward Curves
* Learning Progress
* Win Rate Evolution
* Policy Stability Metrics

---

## Opponent Modeling

Tracks player tendencies including:

* VPIP
* PFR
* Aggression Factor
* Fold-to-Raise
* Bluff Frequency

Player Classification:

* Tight Passive
* Tight Aggressive
* Loose Passive
* Loose Aggressive

AI agents adapt dynamically based on observed behavior.

---

## Explainable AI

Every AI action includes detailed reasoning:

Example:

Action: Raise

Confidence: 84%

Reasoning:

* Hand Equity = 67%
* Pot Odds Favorable
* Opponent Over-Folds to Aggression
* Positive Expected Value Detected

The platform provides transparent decision explanations rather than black-box outputs.

---

## Analytics Dashboard

Professional research dashboard featuring:

* Equity Calculator
* Hand Range Analyzer
* Bluff Heatmaps
* Decision Trees
* Tournament Statistics
* Performance Metrics
* Agent Comparison Tools

Inspired by institutional quantitative research platforms.

---

## AI Tournament Engine

Run large-scale simulations between agents.

Features:

* Round Robin Tournaments
* Knockout Competitions
* ELO Ratings
* Agent Rankings
* Statistical Analysis

Generate performance reports automatically.

---

## Research Laboratory

Designed for experimentation.

Capabilities:

* Algorithm Benchmarking
* Hyperparameter Sweeps
* Strategy Evaluation
* Policy Comparison
* Reproducible Experiments

Perfect for AI research and academic exploration.

---

# System Architecture

Frontend

```text
Next.js
TypeScript
TailwindCSS
Recharts
```

Backend

```text
FastAPI
Python
Pydantic
REST APIs
```

Machine Learning

```text
PyTorch
Stable Baselines3
NumPy
Pandas
```

Infrastructure

```text
PostgreSQL
Redis
Docker
GitHub Actions
```

---

# Architecture Diagram

```text
                   ┌───────────────────┐
                   │    Frontend UI    │
                   └─────────┬─────────┘
                             │
                             ▼
                   ┌───────────────────┐
                   │     FastAPI       │
                   └─────────┬─────────┘
                             │
         ┌───────────────────┼───────────────────┐
         ▼                   ▼                   ▼

 ┌─────────────┐   ┌─────────────┐   ┌─────────────┐
 │ CFR Engine  │   │ MCTS Engine │   │ RL Engine   │
 └─────────────┘   └─────────────┘   └─────────────┘

         └───────────────┬───────────────┘
                         ▼

               ┌─────────────────┐
               │ Poker Simulator │
               └─────────────────┘

                         ▼

               ┌─────────────────┐
               │ PostgreSQL DB   │
               └─────────────────┘
```

---

# Project Structure

```text
project-chimera/

├── backend/
│   ├── api/
│   ├── poker_engine/
│   ├── agents/
│   ├── training/
│   ├── tournaments/
│   └── analytics/
│
├── frontend/
│   ├── app/
│   ├── components/
│   ├── pages/
│   └── dashboard/
│
├── models/
│
├── reports/
│
├── datasets/
│
├── docker/
│
├── tests/
│
└── docs/
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/project-chimera.git

cd project-chimera
```

---

## Backend Setup

```bash
cd backend

pip install -r requirements.txt

uvicorn main:app --reload
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

---

## Docker

```bash
docker-compose up --build
```

---

# Example Use Cases

## Human vs AI

Challenge an advanced poker agent and receive real-time explanations for every decision.

## AI Tournament

Run 10,000 simulated matches between:

* CFR+
* PPO
* MCTS

and compare long-term profitability.

## Strategy Analysis

Upload hand histories and analyze:

* Mistakes
* Missed Opportunities
* Bluff Frequencies
* EV Losses

---

# Performance Metrics

Project Chimera evaluates agents using:

* Win Rate
* ELO Rating
* Expected Value (EV)
* Regret
* Exploitability
* Nash Distance
* Policy Stability
* Decision Confidence

---

# Future Work

Planned enhancements:

* Deep CFR
* Neural CFR
* Transformer-Based Opponent Modeling
* Multi-Table Simulations
* Distributed Self-Play Clusters
* LLM-Powered Strategy Coach
* Real-Time Voice Commentary
* Reinforcement Learning from Human Feedback (RLHF)

---

# Research Applications

Project Chimera can be extended to:

* Quantitative Finance
* Market Making
* Auction Design
* Supply Chain Optimization
* Autonomous Negotiation Systems
* Strategic Resource Allocation
* Multi-Agent Planning

---

# Resume Impact

Project Chimera demonstrates expertise in:

* Artificial Intelligence
* Reinforcement Learning
* Game Theory
* Distributed Systems
* Full Stack Engineering
* Explainable AI
* Quantitative Modeling
* Machine Learning Research

---

# Author

Hoshika Gupta

