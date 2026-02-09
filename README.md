# EMT Metabolism Model

This repository contains a Python implementation of the **Cancer metabolism model** published in:  
https://doi.org/10.1038/s41540-025-00525-x

The structure mirrors the original MATLAB implementation 


The model includes:
- ODEs for ROS / AMPK / HIF-1 signaling (Equations 1–5)
- Algebraic metabolic flux equations (Equations 6–22)
- ATP production and consumption bookkeeping (Equations 23–31)

---

## Contents

1. Shifted Hill functions and competitive combiners  
2. Default parameters  
3. Flux equations (algebraic) and solver  
4. ODEs for A, H, mtROS, and noxROS  
5. Simulation helper functions  
6. Example run and plots  

---

## Installation

### Requirements
- Python 3.10.19

### Setup

Install dependencies using:

```bash
pip install -r requirements.txt
