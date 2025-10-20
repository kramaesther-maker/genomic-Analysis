# GenomicsAnalysis

This project analyzes genomic sequencing data to identify read-level patterns and produce QC plots and summary tables.

## Dependencies
- Python 3.10+
- Python packages: numpy, pandas, matplotlib
- Optional: Docker for containerized runs

## Required input
- FASTQ files (paired-end) in `input/fastq/`
- A sample metadata CSV: `samples.csv`

## Output
- QC plots in `results/plots/`
- Sample summary tables in `results/tables/`
- Final report: `results/report.html`

## Quick start (local)
```bash
python3 Scripts/main_script.py --input input/fastq/ --metadata samples.csv --out results/
