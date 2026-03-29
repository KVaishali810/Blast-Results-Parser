# BLAST Results Parser & Annotator

A Python notebook that parses BLAST results, filters significant
hits and produces an annotated biological report.

## What it does
- Parses simulated BLAST output (7 hits)
- Filters by E-value < 1e-5 and Identity > 50%
- Annotates significant hits with gene function,
  pathway and disease association
- Saves annotated report to CSV
- Visualizes identity% and significance scores

## Libraries used
- pandas — data filtering and CSV export
- numpy — log10 calculations
- matplotlib — visualization

## Key results
- 5/7 hits passed significance filters
- Top hit: BRCA1 (E-value=1e-120, Identity=98.5%)
- All significant hits are cancer-related genes

## Key concepts learned
- E-value interpretation
- BLAST hit filtering
- Biological annotation
- pandas filtering with multiple conditions

## Author
K Vaishali
MSc Bioinformatics
C Projects      ✅ 5/5 complete
Python Projects ✅ 5/5 complete
R Projects      ⏳ 0/5 remaining
