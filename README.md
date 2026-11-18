# QBISAC allocation and local ranging
QBISAC_allocation.ipynb contains Figures 5.1–5.7 from Quantum Backscatter Communication and Local Ranging: Allocation under Count and Energy Limits, UNSW Thesis C.

## Run the notebook

Tested with Python 3.12.14. From the notebook folder, run

```
python -m pip install "jupyterlab==4.6.6" "ipykernel==7.4.0" "numpy==2.5.5" "matplotlib==3.11.2" "matplotlib-inline==0.2.2"
python -m jupyterlab QBISAC_allocation.ipynb
```

In JupyterLab, choose Restart Kernel and Run All Cells.



| Entry | How it is used |
| --- | --- |
| central | Figure 5.1 and Tables 5.1 and 5.4. Check the recalculated mode coefficients, allocation counts and integer bounds against the thesis values. |
| energy_witnesses | Figure 5.2. Recalculate the energy interval for each of 211 saved allocations. |
| figures | Draw the saved optimisation results for Figures 5.3, 5.4 and 5.6, and check points on the other curves. |
| memory_lifetimes | Figure 5.5. Recalculate paired and coherent scores and check their bounds at four idler lifetimes. |
| weak_cases | Figure 5.7(b). Check feasibility and score loss for 18 weak-return designs. Panel (a) calculates the timing curves directly. |

