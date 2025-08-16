This repository contains code, configuration, data-preparation scripts, reproducibility instructions, and resource logs supporting the manuscript. For manuscript text, notation, constants and derivations, see the paper source in this repo (LaTeX) and the `manuscript/` directory. 

Abstract 
This project implements and reproduces experiments for an operator–algebraic QCNN pipeline that integrates symmetry-preserving padding, quantum phase estimation (QPE), and amplitude amplification (AA). Benchmarks include MNIST and FashionMNIST (reported peak accuracies in manuscript: MNIST 98.7%, FashionMNIST 94.7%). The repository provides scripts to (i) prepare and preprocess datasets, (ii) run simulator and small-hardware experiments, (iii) collect resources and noise logs, and (iv) reproduce tables and figures from the manuscript. 

Requirements

Recommended: Linux/macOS, Python 3.9+.
Python packages (example `requirements.txt` provided):
