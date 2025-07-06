# LDPC Decoding for 5G NR 

This repository contains my project work for simulating LDPC (Low-Density Parity-Check) Decoding in the context of 5G NR. The simulation includes BPSK modulation, AWGN channel modeling, LDPC encoding/decoding, and performance evaluation.

📋 Project Description
The objective of this project is to:

Perform BPSK Modulation & AWGN Channel Simulation

Implement LDPC Soft Decision and Hard Decision Decoders

Evaluate Performance via Monte Carlo Simulations

The project uses the Base Graph 2 (BG2) for LDPC codes, following the 5G NR standard, with configurable lifting size and code rates.

🔧 Features
LDPC Parity-Check Matrix Generation (5G NR BG2)

BPSK Modulation

AWGN Channel Simulation

Soft Decision & Hard Decision Message Passing Decoders using Tanner Graph

Performance Metrics:

Probability of Decoding Success

Algorithm Convergence vs. Iterations

Monte Carlo Simulation across SNR range

Benchmark comparison with Shannon Capacity and Normal Approximation
