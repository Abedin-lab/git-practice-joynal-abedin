# Project Description

This project is a CLI-based calculator program built in Python. Its primary purpose is to serve as a hands-on practical assignment for practicing essential Git & GitHub workflows, including branching strategies, staging, committing, merging, and remote repository synchronization.

## Technical Details

- **Language**: Python 3
- **Modules**: The utility arithmetic functions are imported dynamically inside `main.py` using absolute and relative importing mechanisms.

## Git Branching Workflow

This project utilized a feature-branching workflow to ensure a clean codebase. Two main feature branches were created and merged:
1. `feature/calculator`: Created to isolate development of the basic `add` and `subtract` operations. Merged back to `main` via fast-forward merging.
2. `feature/error-handling`: Created to isolate development of robust division-by-zero checks. Merged back to `main` to finalize features.