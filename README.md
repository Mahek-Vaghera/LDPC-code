# 🚀 LDPC Decoding for 5G NR  

This repository contains my project work for simulating **LDPC (Low-Density Parity-Check) Decoding** in the context of **5G NR (New Radio)**.  
The simulation includes:
- **BPSK Modulation**
- **AWGN Channel Modeling**
- **LDPC Encoding & Decoding**
- **Performance Evaluation**

---

## 📋 Project Description  

The objective of this project is to:
- ✅ Perform **BPSK Modulation** & **AWGN Channel** Simulation  
- ✅ Implement **LDPC Soft Decision** and **Hard Decision** Decoders  
- ✅ Evaluate Performance via **Monte Carlo Simulations**

This project uses **Base Graph 2 (BG2)** for LDPC codes, following the **5G NR standard**, with configurable **lifting size** and **code rates**.

---

## 🔧 Features  

- **LDPC Parity-Check Matrix Generation** (5G NR BG2)
- **BPSK Modulation**
- **AWGN Channel Simulation**
- **Soft Decision & Hard Decision** Message Passing Decoders (using **Tanner Graph**)
- Performance Metrics:
  - 📈 **Probability of Decoding Success**
  - 🔄 **Algorithm Convergence vs. Iterations**
  - 🧪 **Monte Carlo Simulation** across SNR range
- 📊 **Benchmark Comparison** with:
  - **Shannon Capacity**
  - **Normal Approximation**

---
