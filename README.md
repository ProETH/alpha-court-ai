# AI Verdict

> **An AI-powered Capital Commitment Validation Skill for the CoinW AI Trading Skill Challenge.**

AI Verdict is an explainable AI trading Skill designed to validate trading opportunities before execution.

Unlike traditional trading strategies that focus on generating buy or sell signals, AI Verdict evaluates whether sufficient market evidence exists to support a trading decision.

The framework is built around **Capital Commitment Score (CCS)**, a proprietary metric that measures the relationship between **Net Buy** and **Daily Trading Volume** across multiple trading sessions.

---

# Why AI Verdict?

Many trading systems react to price movements.

AI Verdict asks a different question:

> **"Is real capital entering the market, or is this simply temporary speculation?"**

Instead of predicting the future, the AI validates whether market participation is strong enough before supporting capital allocation.

---

# Key Features

- AI-powered trading validation
- Explainable decision-making
- Capital Commitment Score (CCS)
- Multi-day confirmation framework
- Risk-aware analysis
- AI Agent ready
- Designed for the CoinW AI ecosystem

---

# Strategy Overview

The strategy evaluates market participation using a proprietary indicator called the **Capital Commitment Score (CCS)**.

Formula:

```
CCS = Net Buy / Daily Trading Volume
```

Rather than relying on a single trading session, AI Verdict analyzes the latest **three consecutive trading days** to identify whether buying commitment is strengthening or weakening.

This approach helps reduce false signals caused by short-term market activity.

---

# Repository Structure

```
AI-Verdict/
├── README.md
├── SKILL.md
├── ai-verdict-example.md
└── LICENSE
```

---

# Documentation

This repository contains:

**README.md**

Project overview.

**SKILL.md**

Complete strategy specification including:

- Strategy logic
- Parameters
- Agent execution flow
- Risk management
- Output format

**ai-verdict-example.md**

A complete simulation demonstrating how AI Verdict evaluates market data and generates an explainable trading decision.

---

# AI Agent Workflow

```
Collect Market Data
        │
        ▼
Calculate CCS
        │
        ▼
Validate Market Evidence
        │
        ▼
Analyze Risk
        │
        ▼
Generate AI Verdict
```

---

# CoinW AI Agent Integration

AI Verdict is designed to operate as an AI Agent within the CoinW AI ecosystem.

The Skill can assist traders by validating investment opportunities before execution while providing transparent reasoning behind every decision.

The framework is compatible with CoinW's long-term vision of AI-powered trading and Agent collaboration.

---

# Risk Notice

AI Verdict is an AI decision-support framework.

It does not predict future prices and should never be considered financial or investment advice.

Users remain fully responsible for all trading decisions.

---

# License

Released under the MIT License.

---

# Disclaimer

This repository was created for the **CoinW AI Trading Skill Challenge**.

All examples use simulated market data for educational and demonstration purposes only.
