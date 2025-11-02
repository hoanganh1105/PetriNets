# Symbolic and Algebraic Reasoning in Petri Nets

This project implements a series of tasks for the **Mathematical Modeling (CO2011)** course at HCMUT.

## Structure
- `src/parser/` – PNML parser and model representation
- `src/reachability/` – explicit and symbolic reachability computation
- `src/analysis/` – ILP-based deadlock detection and optimization
- `data/` – sample PNML test files
- `report/` – final report and figures

## How to Run
```bash
pip install -r requirements.txt
python src/parser/pnml_parser.py data/example.pnml
