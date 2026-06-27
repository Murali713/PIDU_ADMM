# Physics-Informed Deep Unfolding Framework for Bearing Fault Diagnosis

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red.svg)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()

> **Physics-Informed Deep Unfolding Framework for Bearing Fault Diagnosis Under Variable Speed and Load Conditions** 

## Overview

This repository implements a **Physics-Informed Deep Unfolding (PIDU)** framework for intelligent bearing fault diagnosis under varying speed and load conditions.

The proposed method unfolds the Alternating Direction Method of Multipliers (ADMM) iterations of Variational Mode Decomposition (VMD) into a trainable deep neural network while incorporating physics-based bearing characteristic frequencies.

Unlike conventional deep learning methods, PIDU provides:

- Physics-guided signal decomposition
- Interpretable deep unfolding architecture
- Adaptive spectral masking
- Hilbert envelope feature enhancement
- End-to-end trainable optimization
- Robust diagnosis under variable operating conditions
- **simplified executable pseudocode implementation of the proposed PIDU framework**
- ## Repository Structure

```
PIDU/
│
├── datasets/
│   ├── CWRU/
│   └── Experimental/
│
├── models/
│   ├── pidu.ipynb
