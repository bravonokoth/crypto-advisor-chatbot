# Week 1 Assignment: Cryptocurrency Advisor Chatbot

This repository contains the solution for the Week 1 Assignment of PLP Academy, building a rule-based **Cryptocurrency Advisor Chatbot** named **CryptoBuddy**. The chatbot provides investment advice based on profitability (price trends, market cap) and sustainability (energy use, sustainability score).

## Project Overview

**Objective**: Create an AI-driven chatbot that analyzes cryptocurrency data and offers advice using simple rule-based logic.

**Theme**: "Your First AI-Powered Financial Sidekick!" 🌟

**Tools**:
- Language: Python
- Logic: `if-else` statements for conversational flow
- Dataset: Predefined crypto data (Bitcoin, Ethereum, Cardano)
- Platform: Developed in [Google Colab/Jupyter Notebook/IDE]

## Features

1. **Chatbot Personality**:
   - Name: CryptoBuddy
   - Tone: Friendly and engaging with emojis (🚀, 🌱)
   - Includes a risk disclaimer: "Crypto is risky—always do your own research!"

2. **Chatbot Logic**:
   - Handles queries about profitability (e.g., "Which crypto is trending up?") by prioritizing coins with `price_trend = "rising"` and `market_cap = "high"`.
   - Recommends sustainable coins (e.g., "What’s the most sustainable coin?") based on `sustainability_score > 7/10` and low `energy_use`.
   - Provides detailed info for specific coins (e.g., "Info about Ethereum").
   - Falls back to default responses for unrecognized queries.

3. **Dataset**:
   - Includes Bitcoin, Ethereum, and Cardano with attributes: `price_trend`, `market_cap`, `energy_use`, and `sustainability_score`.

## Files
- `crypto_advisor.py`: The main Python program implementing the chatbot.
- `README.md`: This file, documenting the project and usage instructions.