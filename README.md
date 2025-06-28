# T-STRUCTGAD: Deep Temporal and Structural Embeddings for Robust Unsupervised Anomaly Detection in Dynamic Graphs

T-STRUCTGAD is an unsupervised framework for detecting anomalies in dynamic graphs, where both structure and behavior evolve over time. It combines Graph Convolutional Gated Recurrent Units (GConvGRUs) and Long Short-Term Memory (LSTM) networks to learn deep node representations across time steps. Anomalies are detected using reconstruction errors from an AutoEncoder, making the model robust to both subtle and abrupt irregularities in graph dynamics.

---

## 🚀 Features

- **Temporal + Structural Modeling**: Integrates GConvGRUs and LSTMs to capture both graph structure and time evolution.
- **Unsupervised Anomaly Detection**: No labels or supervision required; anomalies are detected using reconstruction loss.
- **Robust to Subtle Deviations**: Detects minor shifts as well as major structural changes in evolving graphs.
- **Strong Empirical Performance**: Outperforms 12 state-of-the-art methods on 4 real-world datasets.

---

## 📁 Getting Started

Follow these steps to use the dataset and run benchmarks.

### 1. Clone the Repository

```bash
git clone https://github.com/KurbainIntelligenceLab/tstruct-gad.git
cd tstruct-gad
```

## 2. Required Directory Structure

Before going through the .ipynb file, please ensure the following directories exist in the project root:

```bash
mkdir data
mkdir tgn_node_embeddings
```

