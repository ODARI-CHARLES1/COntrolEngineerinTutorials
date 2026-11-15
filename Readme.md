 

# CONTROL ENGINEERING I

## Time Response Analysis Using Python

### Overview

This practical explores the time-domain response of control systems using Python. It covers impulse, step and ramp responses, numerical simulation, plotting and performance analysis.

### Learning Objectives

- Understand time response.
- Define transfer functions.
- Simulate impulse, step and ramp responses.
- Plot and interpret response curves.
- Determine time-domain performance specifications.

### Requirements

- Python 3
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

### Environment Setup

**1. Create virtual environment**

```bash
python3 -m venv control.venv
```

**2. Activate environment**

Linux:

```bash
source control.venv/bin/activate
```

Windows:

```bash
control.venv\Scripts\activate.bat
```

**3. Install dependencies**

```bash
pip install numpy scipy matplotlib jupyter lab
```

**4. Launch Jupyter**

```bash
jupyter lab
```

### Python Imports

```python
iimport numpy as np
import matplotlib.pyplot as plt
from control import matlab as mt
```

### Topics Covered

1. Transfer functions.
2. Standard test signals.
3. First-order systems.
4. Second-order systems.
5. Impulse response.
6. Step response.
7. Ramp response.
8. Time-domain specifications.

### Practical Instructions

Run the notebook cells sequentially, observe the plots and analyse the resulting system responses.

### Author

Control Engineering I – Practical Laboratory
