# Covariance Change-Point Detection in Resting-State fMRI

University project. It tests whether brain network connectivity changes abruptly within a single fMRI scan, using the Li & Li (2023) covariance change-point statistic on 781 resting-state scans from a Kaggle dataset.

About 28–31% of scans show at least one change, against 2–3% of no-change copies. This is evidence of non-stationary connectivity, not proof of abrupt events, because motion could not be ruled out.

The notebooks in `notebooks/` are the executed runs, with outputs:

- `01-audit`, `01b-audit-followup`: data audit
- `01c-theory-checks`: values for the theory
- `03-final`: full detection pipeline
- `04-burst-check`: artifact check

They ran on Kaggle, and the data is not included.
