# DeFi Yield Portfolio Analytics

## Overview
This project builds a data pipeline and analytics framework for constructing and monitoring
a DeFi yield portfolio. It consolidates yield, TVL, and pricing data across protocols and
produces portfolio optimization recommendations under liquidity and risk constraints.

## Features
- Automated ingestion from DefiLlama + CoinGecko
- Cleaned consolidated datasets stored in PostgreSQL
- Yield sustainability & bias detection analysis
- Portfolio optimization (constraints + risk limits)
- Stress testing under DeFi-specific scenarios
- CIO-ready reporting outputs

## Data Sources
- DefiLlama API
- CoinGecko API

## How to Run
1. Install requirements
2. Add config.yaml
3. Run pipeline script

## Outputs
- Clean datasets (processed/)
- Portfolio allocation recommendations
- Risk metrics dashboard and charts
- Investment committee memo
