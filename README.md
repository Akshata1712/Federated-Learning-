# Federated-Learning-
Studying convergence behavior of federated learning models for credit card fraud detection
This repository contains ongoing research on the convergence of federated learning (FL) models applied to credit card fraud detection. The goal is to understand how heterogeneous models (different architectures across clients) affect convergence, stability, and performance in privacy-preserving collaborative training.

## Implemented So Far

FedAvg with homogeneous models to establish baseline convergence behavior.
Heterogeneous model setups with capacity-aware aggregation to improve stability across diverse client models.
Metrics tracked: Accuracy, F1-score, and Binary Cross-Entropy loss over training rounds.

## Preliminary Insights

Homogeneous models converge reliably with high accuracy (~98%).
Naive heterogeneous aggregation is unstable; incorporating capacity-aware aggregation significantly improves convergence stability.

## Ongoing Work

Exploring knowledge distillation and advanced aggregation strategies to further enhance convergence in heterogeneous federated learning settings.
