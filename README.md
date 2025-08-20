# Clinical Report Summarisation with LLMs (MSc Project)

Code and Colab notebooks for **Using LLMs in Text Summarisation of Radiology Reports**.

## Notebooks
- `FINAL_MIMIC_CXR.ipynb` — FLAN‑T5 fine‑tuning & eval on MIMIC‑CXR (Findings → Impression)
- `FINAL_MIMIC_III.ipynb` — BioBART fine‑tuning & eval on MIMIC‑III discharge summaries

## Datasets
- MIMIC‑CXR: chest X‑ray reports (PhysioNet access required)
- MIMIC‑III: ICU notes (PhysioNet access required)

## Results (ROUGE)
- **MIMIC‑CXR (FLAN‑T5)**: R‑1=0.5589, R‑2=0.4490, R‑L=0.5319, R‑Lsum=0.5442  
- **MIMIC‑III (BioBART)**: R‑1=0.3709, R‑2=0.1798, R‑L=0.2848, R‑Lsum=0.3553

## Reproduce (Colab)
1. Open a notebook in Colab → Runtime → Change runtime type (GPU if available).
2. Update dataset paths to your Drive/PhysioNet files.
3. Run all cells to preprocess, train, and evaluate.

## Citation
[Your Name], *MSc Dissertation*, Queen Mary University of London, 2025.
