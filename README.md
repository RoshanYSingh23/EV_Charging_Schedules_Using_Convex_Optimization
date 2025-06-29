
# Optimization of Residential EV Charging Schedules via Convex Programming

This project implements and analyzes multiple optimization techniques to minimize the total cost of electric vehicle (EV) charging over a 24-hour period. The optimization problem incorporates time-of-use (TOU) electricity pricing and a quadratic battery degradation cost.

We explore:
- A closed-form solution via Karush–Kuhn–Tucker (KKT) conditions,
- Projected Gradient Descent (PGD),
- Exponential Gradient Descent (EGD), and
- Accelerated Gradient Descent (AGD).

The data for hourly electricity prices and EV charging sessions is sourced from public datasets.

---

## 📁 Directory Structure

```
EV_Charging_Schedules_Using_Convex_Optimization/
├── convex.ipynb               # Jupyter notebook containing all code
├── Report.pdf                 # Full report with derivations, plots, and analysis
├── references.bib             # LaTeX bibliography file for citations
└── content/
    ├── price.xlsx             # Hourly electricity pricing data
    └── station_data_dataverse.csv  # EV charging session data
```

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/RoshanYSingh23/EV_Charging_Schedules_Using_Convex_Optimization.git
   cd EV_Charging_Schedules_Using_Convex_Optimization
   ```

2. Install required Python packages:
   You can install the required packages using `pip`:
   ```bash
   pip install numpy pandas matplotlib
   ```

   > Or run inside a Jupyter environment like Google Colab (no installation needed if using Colab).

---

## 🚀 How to Run

1. Open the notebook:
   - If using local Jupyter:
     ```bash
     jupyter notebook convex.ipynb
     ```
   - Or upload `convex.ipynb` to [Google Colab](https://colab.research.google.com) for easy execution.

2. Make sure the following files are accessible in the working directory:
   - `content/price.xlsx`
   - `content/station_data_dataverse.csv`

3. Run all cells in the notebook to:
   - Load and visualize the data
   - Solve the convex optimization problem using multiple methods
   - Generate and compare schedules and cost metrics

---

## 👤 Author

**Roshan Y Singh**
