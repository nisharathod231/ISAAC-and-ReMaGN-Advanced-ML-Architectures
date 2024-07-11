# Advanced ML Architectures: ISAAC and ReMaGN

## Assignment 5 - E0294: Systems for Machine Learning

**Author:** Pritam Trilochan Gouda  
**Affiliation:** CSA, IISc  
**Date:** April 18, 2024

---

## Overview

This repository contains the solutions and discussions for Assignment 5 of the course E0294: Systems for Machine Learning. The assignment covers two advanced machine learning architectures: ISAAC and ReMaGN.

## Table of Contents

- [Introduction](#introduction)
- [ISAAC Architecture](#isaac-architecture)
  - [Overview](#overview)
  - [Efficiency Metrics](#efficiency-metrics)
  - [Design Flaws and Improvements](#design-flaws-and-improvements)
- [ReMaGN Architecture](#remagn-architecture)
  - [Overview](#overview-1)
  - [Computation Layers](#computation-layers)
  - [Efficiency and Performance](#efficiency-and-performance)
- [Assignment Questions](#assignment-questions)
- [Files Included](#files-included)
- [Usage](#usage)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction

This assignment delves into the intricacies of the ISAAC and ReMaGN architectures, exploring their unique approaches to enhancing machine learning system efficiency and performance.

## ISAAC Architecture

### Overview

ISAAC (In-Situ Analog Arithmetic Computation) integrates memory and computation to enable highly efficient machine learning systems. This architecture significantly reduces latency and energy consumption by performing multiply-accumulate (MAC) operations directly at the memory units.

### Efficiency Metrics

- **Computational Efficiency:** 478.8 GOPS/s ×mm²
- **Power Efficiency:** 383.7 GOPS/W

### Design Flaws and Improvements

While ISAAC demonstrates superior efficiency, its computational resources in the neural network's final stages are not fully optimized. Further design enhancements are needed to exploit its full potential.

## ReMaGN Architecture

### Overview

ReMaGN (ReRAM-based Graph Neural Network) architecture represents a significant leap in GNN training efficiency. It employs on-chip ReRAM-based computation for vertex and edge operations, essential for GNN learning.

### Computation Layers

- **Vertex-centric (V-layer) Computation**
- **Edge-centric (E-layer) Computation**

### Efficiency and Performance

ReMaGN uses a 3-D mesh topology and 3-D toroidal Network-on-Chip (NoC) for high-speed data communication, achieving remarkable energy efficiency and performance compared to traditional GPUs.

## Assignment Questions

1. **ISAAC Architecture**: Detailed analysis of its design and efficiency.
2. **ReMaGN Architecture**: Exploration of its computation methods and performance metrics.
3. **Floating-Point Communication**: Calculation of bits communicated between layers in a neural network.

## Files Included

- `23754_Assignment_5.pdf`: The complete assignment document.
- `question3.ipynb`: Jupyter notebook for part (a) of Question 3.

## Output

![image](https://github.com/pritamgouda11/ISAAC-and-ReMaGN-Advanced-ML-Architectures/assets/46958858/542d47e8-4282-49ea-8f19-beb12d8775c7)


## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/advanced-ml-architectures.git
   cd advanced-ml-architectures

