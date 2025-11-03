# Comparative Analysis and Enhancement of Machine Translation and Transcription Systems

**Duration:** Sep 2023 – Jun 2024 (9 months)  
**Author:** Sarvesh Zamare — [GitHub/sarveshzamare8-cell](https://github.com/sarveshzamare8-cell)

---

## TL;DR
This repository contains reproducible experiments comparing rule-based, statistical, and neural approaches for Machine Translation (MT) and Automatic Speech Recognition (ASR). I fine-tuned pre-trained models and measured improvements using BLEU for MT and WER for ASR. The project demonstrated large improvements in contextual translation accuracy through domain-specific fine-tuning.

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
