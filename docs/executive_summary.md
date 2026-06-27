# Executive Summary

## Project title

**Predictive Maintenance & Asset Reliability: RUL Prediction Using LSTM-MHSA**

## Summary

This project demonstrates how deep learning can support predictive maintenance by estimating the remaining useful life of high-reliability equipment. The model combines Long Short-Term Memory and Multi-Head Self-Attention to learn degradation patterns from sensor time-series data.

## Business problem

High-reliability equipment often fails rarely, which means organizations may have only a limited number of complete run-to-failure histories. This creates a challenge for predictive maintenance because models need enough degradation examples to estimate remaining useful life accurately.

## Proposed solution

The proposed approach uses:

- LSTM to capture temporal dependencies in degradation signals
- MHSA to extract information from all hidden states
- Fully connected layers to produce a scalar RUL prediction

## Case study

The paper applies the model to a simulated heterogeneous fleet of aluminium electrolytic capacitors used in electric vehicle powertrains. The monitored signals are equivalent series resistance and working temperature.

## Key result

The proposed model achieved the best combined prognostics metric among the tested models and remained robust even when only five complete run-to-failure trajectories were available.
