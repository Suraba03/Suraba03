# Viacheslav (Slava) Chekmenev

ML / LLM engineer in Almaty, Kazakhstan. I make LLM systems measurable and reliable in production: evaluation on live traffic, LLM-as-a-judge annotation, and serving NLP models under load.

**Website:** [suraba03.github.io/Suraba03](https://suraba03.github.io/Suraba03/) (English / Russian)

## What I work on

**T-Bank, LLM Platform** — LLM Engineer, Jul 2025 – now

- Feature lead for production quality monitoring of a real-time PII-anonymization service that sits in front of internal LLM apps and AI coding assistants: live-traffic sampling, LLM + human annotation, per-entity NER metrics, drift alerts, dashboards.
- Two-stage LLM annotator (Qwen3-235B on vLLM proposes, a smaller model verifies). Error analysis took precision at 0.8 recall from 0.10 to 0.59.
- The monitoring data drove retraining and rule fixes: detector recall 0.80 → 0.95.
- Root-caused a serving incident in Triton's ONNX Runtime backend and drove the move to TensorRT: p99 latency −50% at quality parity.

**Sberbank** — Data Scientist (Model Risk), 2023 – 2025

- Validated 20+ production models; built an AutoML challenger-model pipeline; co-built the bank's first testing framework for LLM apps and RAG.

Most of this work is internal, so it isn't here. What is here:

## Code

- [**anki_manga**](https://github.com/Suraba03/anki_manga) — in progress. Chrome extension plus a local helper for reading Japanese manga: speech bubbles are OCR'd locally and laid invisibly over the page so Yomitan works on them, with furigana, translation and grammar notes on click (DeepSeek, your own API key) and one-click Anki cards.
- [**bsc-thesis-ppg-diabetes-hypertension**](https://github.com/Suraba03/bsc-thesis-ppg-diabetes-hypertension) — screening for type 2 diabetes and hypertension from photoplethysmography: wavelet images + VGG / Swin Transformer, Flask demo, English preprint.

## Stack

`Python` · `PyTorch` · `Transformers` · `vLLM` · `Triton Inference Server` · `ONNX Runtime` · `TensorRT` · `Airflow` · `Kafka` · `SQL` · `CatBoost`

## Contact

[chekmenev031@gmail.com](mailto:chekmenev031@gmail.com) · [LinkedIn](https://www.linkedin.com/in/Suraba03) · [Telegram](https://t.me/suraba03)
