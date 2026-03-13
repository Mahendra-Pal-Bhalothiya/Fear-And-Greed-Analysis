# Crypto Fear & Greed Trading Analysis

A comprehensive data analysis project examining the relationship between market sentiment (Fear & Greed Index) and cryptocurrency trading behavior across multiple accounts.

## Project Overview

This project analyzes trading data from three distinct accounts over multiple years, combining it with the Crypto Fear & Greed Index to uncover patterns, insights, and actionable trading strategies. The analysis includes performance metrics, behavioral analysis, sentiment correlations, and predictive modeling.

## Dataset

The analysis uses two primary datasets:

1. **Fear & Greed Index** (`fear_greed_index.csv`)
   - 2,642 daily records from 2018-02-01 to 2025-05-02
   - Contains timestamp, index value (0-100), and sentiment classification

2. **Historical Trading Data** (`historical_data.csv`)
   - 2,026 trades across 3 accounts
   - Includes trade details: price, size, PnL, fees, timestamps
   - Covers multiple cryptocurrencies (BTC, ETH, SOL, etc.)

## Setup Instructions

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. **Clone the repository**

```bash
git clone <repository-url>
cd crypto-fear-greed-analysis
```
