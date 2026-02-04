# Cross-Encoder IR Pipeline

<p align="center">
  <img src="assets/Screenshot%20(562).png" width="40%" />
  <img src="assets/Screenshot%20(563).png" width="40%" />
</p>

This repository contains notebooks and report artifacts for a project on
cross-encoder re-rankers, ensemble methods, and LLM-based query expansion.

## Contents
- `finetune_cross_encoders.ipynb`  
  Fine-tuning three cross-encoder models and recording training steps.
- `ranx_ensemble_methods.ipynb`  
  Ensemble fusion methods (ranx) for Tasks 2–3, including combinations.
- `query_expansion_prf.ipynb`  
  LLM query expansion with pseudo-relevance feedback (Task 5).
- `IR_finalAssignment.pdf`  
  Final report (PDF).

## Project Summary
The work follows the official 2025 IR project brief:

1. **Fine-tuning and evaluation (Task 1)**  
   Fine-tune three cross-encoders for one hour each, evaluate on TREC DL’19,
   and report NDCG@10, Recall@100, MAP@1000 plus training steps.

2. **Ensemble methods with ranx (Tasks 2–3)**  
   Apply five fusion methods to the three run files, evaluate them, then apply
   the best fusion method to all pairwise model combinations.

3. **LLM query expansion (Tasks 4–5, optional)**  
   Implement prompt-based query expansion, then extend it with
   pseudo-relevance feedback using top-3 documents.

## Notes
- The report is required as a PDF (no ZIP submission).
- Model names used for fine-tuning:
  - `cross-encoder/ms-marco-MiniLM-L-2-v2`
  - `cross-encoder/ms-marco-TinyBERT-L-2-v2`
  - `distilroberta-base`

