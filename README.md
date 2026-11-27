# Rosalind Solutions (Python)

Solving Rosalind bioinformatics problems in Python to learn coding fundamentals, string and sequence handling.

## Question
Can I solve classic bioinformatics problems from scratch in Python, with clean, tested, reproducible code?

## Data
Problems from Rosalind (https://rosalind.info/problems/list-view/).
Each solution is in `scripts/` and named by Rosalind ID, e.g. `dna.py`, `rna.py`, `revc.py`.

## Methods
- Language: Python 3
- No external packages for core solutions - standard library only
- Each script reads input, solves the problem, prints output

## How to reproduce
```bash
conda env create -f environment.yml
conda activate rosalind
python scripts/dna.py
rosalind-solutions/
├── scripts/          # One Python file per Rosalind problem
├── results/          # Figures and tables (figures/, tables/)
├── docs/             # Notes
├── environment.yml   # Conda environment
└── README.md

```

## Key results
Work in progress. Solutions added as I complete them in Months 1-2 of my learning plan.

## Limitations and next steps
- Early solutions prioritise clarity over speed.
- Next: add tests, add more problems, refactor repeated functions.

## References
- Rosalind: https://rosalind.info
- My 12-Month Bioinformatics Career Plan
