# Neural-Network supported 3DVar with Lorenz’63

**Jan Stüwe**, **Pavitra Chandarana**  

_A small, reproducible demo with an optional ML “predicted-increments” variant._

> This repository provides a single notebook that implements 3D-Var data assimilation on the classic Lorenz–63 chaotic system, plus an experiment that augments 3D-Var with a lightweight ML model that predicts analysis increments. The goal is to be clear, compact, and easy to run for benchmarking and exploration.


---

## What’s inside

- **`code_report.ipynb`** — Main notebook: simulation, 3D-Var, experiments (full vs. partial observations, noise levels, assimilation strides), RMSE plots, and the optional ML-hybrid.
- **`requirements.txt`** — Minimal dependencies for a clean run.
- **`figures/`** — Saved plots if you choose to export them

---

## Quickstart

### 1) Environment
```bash
# Python 3.10+ recommended
python -m venv .venv
source .venv/bin/activate   # on Windows: .venv\Scripts\activate

pip install --upgrade pip
pip install -r requirements.txt
```

### 2) Run the Notebook
```bash
jupyter lab # or: jupyter notebook
```