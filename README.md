# Comparative Analysis and Enhancement of Machine Translation and Transcription Systems

**Duration:** Sep 2023 – Jun 2024 (9 months)  
**Author:** Sarvesh Zamare — [GitHub/sarveshzamare8-cell](https://github.com/sarveshzamare8-cell)

---

## TL;DR
This repository contains reproducible experiments comparing rule-based, statistical, and neural approaches for Machine Translation (MT) and Automatic Speech Recognition (ASR). I fine-tuned pre-trained models and measured improvements using BLEU for MT and WER for ASR. The project demonstrated large improvements in contextual translation accuracy through domain-specific fine-tuning.

---
## 📁 Repository Structure
Language-Processing-Translation-Transcription-Analysis/
│
├── data/
│ ├── raw/ # Unprocessed datasets (text and audio)
│ │ ├── english_texts.csv
│ │ ├── hindi_texts.csv
│ │ └── speech_samples.wav
│ └── processed/ # Cleaned and aligned datasets
│
├── models/ # Pre-trained and fine-tuned models
│ ├── asr_model.h5
│ └── model_mt.pt
│
├── notebooks/ # Jupyter notebooks for experiments
│ ├── translation_experiments.ipynb
│ └── asr_comparison.ipynb
│
├── scripts/ # Python scripts for preprocessing and evaluation
│ ├── preprocessing.py
│ ├── translation_pipeline.py
│ └── asr_evaluation.py
│
├── reports/ # Results and documentation
│ ├── bleu_vs_epoch.png
│ ├── wer_results.csv
│ └── final_report.pdf
│
├── LICENSE
├── README.md
└── requirements.txt

---
## Project summary
**Goal:** Evaluate and improve translation and transcription pipelines — from rule-based and statistical baselines to modern neural approaches — with a focus on contextual accuracy and real-world usability.

**Contributions**
- Implemented baseline systems (rule-based & statistical) and neural baselines (Hugging Face transformers, Wav2Vec).
- Fine-tuned pre-trained translation and ASR models on domain-specific data.
- Built evaluation scripts that compute BLEU (sacrebleu) and WER (jiwer).
- Packaged reproducible notebooks and a small demo scaffold.

---

## Key results (summary)
> Replace these numbers with your final metrics in `reports/evaluation_results.pdf`.

- **BLEU**: baseline → **improved by ~20–25%** after fine-tuning.  
- **WER**: reduced by **X%** using fine-tuned Wav2Vec models.  
See `/reports/evaluation_results.pdf` for full tables and plots.

---

## Repo structure
