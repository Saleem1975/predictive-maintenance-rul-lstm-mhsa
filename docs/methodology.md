# Methodology

## Objective

The objective is to estimate the Remaining Useful Life of high-reliability equipment using condition-monitoring time-series data.

## Input signals

The model uses two sensor-based indicators:

- Equivalent Series Resistance (ESR)
- Working / aging temperature

## Model architecture

The proposed model includes:

1. Input time-series sequence
2. Min-Max scaling
3. LSTM layer
4. Multi-Head Self-Attention layer
5. Fully connected decoder
6. RUL estimate

## Why LSTM-MHSA?

LSTM captures sequential information and long-term dependencies. Multi-Head Self-Attention allows the model to extract information from all hidden states instead of relying only on the last LSTM state.

## Evaluation metrics

The paper evaluates performance using:

- RMSPE
- Accuracy Index
- α-λ accuracy
- Combined metric

Lower RMSPE, lower AI, lower combined metric, and higher α-λ accuracy indicate better performance.
