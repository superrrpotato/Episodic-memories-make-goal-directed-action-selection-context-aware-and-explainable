
# Episodic Memory-Based Goal Selection and Action Planning: Code Repository

This repository contains the code used to generate the results and figures reported in the manuscript on **Episodic Memory-Based Goal Selection and Action Planning**. It includes Jupyter notebooks that demonstrate the process of goal-directed action selection with episodic memories and its relation to cognitive processes.

---

## 1. System Requirements

- **Operating System**: Linux, macOS, or Windows  
- **Python Version**: 3.8 or later  
- **Hardware**: Standard desktop or laptop with ≥8 GB RAM  

### Required Python Packages:
- numpy==1.24  
- scipy==1.10  
- pandas==2.0  
- matplotlib==3.7  
- torch==2.1.0
- networkx==3.1  
- scikit-learn==1.2  
- tqdm==4.66

Install them with:

```bash
pip install -r requirements.txt
```

---

## 2. Installation Guide

1. Clone the repository:

```bash
git clone https://github.com/superrrpotato/Episodic-memories-make-goal-directed-action-selection-context-aware-and-explainable.git
cd Episodic-memories-make-goal-directed-action-selection-context-aware-and-explainable
```

2. Create a virtual environment (recommended):

```bash
python3 -m venv env  
source env/bin/activate      # on Windows: env\Scriptsctivate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

Typical installation time: ~2–3 minutes on a standard desktop.

---

## 3. Demo

To reproduce the figures in the manuscript:

1. Launch Jupyter Notebook:

```bash
jupyter notebook
```

2. Open the notebooks in the following order and run **all** cells in each:

- **Figure2.ipynb**  
- **Figure3.ipynb**  
- **Figure4.ipynb**  
- **Figure5.ipynb**  
- **Figure6.ipynb**  

3. Each notebook generates intermediate results and visualizations.

Expected output: figures and numerical results from the paper  
Estimated runtime: ~5–10 minutes per notebook. Figure4.ipynb runs longer, it may takes 1 day to collect all results.

---

## 4. Instructions for Use

You can adapt the notebooks to your own synthetic or real dataset by modifying the data generation sections (usually near the top of each notebook).

⚠ No external datasets are required. All data used is generated internally.

---

## 5. License

This project is licensed under the MIT License.  
See LICENSE for full terms.

---

## 6. Reproducibility

Running the notebooks in order reproduces all main results and plots presented in the manuscript.

---

## 7. Code Availability Statement

All source code, notebooks, and instructions are available at:  
https://github.com/superrrpotato/Episodic-memories-make-goal-directed-action-selection-context-aware-and-explainable
