# Viacheslav (Slava) Chekmenev

ML / LLM engineer in Almaty, Kazakhstan, open to relocation. By day I make LLM systems measurable and reliable in production. After hours I build language-learning tools with a team of Claude Code agents.

**Website:** [suraba03.github.io/Suraba03](https://suraba03.github.io/Suraba03/) (English / Russian)

## Building now

- [**anki_manga**](https://github.com/Suraba03/anki_manga) — **live on the [Chrome Web Store](https://chromewebstore.google.com/detail/manga-ocr-mining-for-anki/bgfnpifeeclmpfdcahphaiahgafjppeo)**. Read Japanese manga in the browser: on-device OCR of speech bubbles (ONNX Runtime Web, WebGPU / WASM), furigana, dictionary lookups, short grammar explanations, one-click Anki cards with the panel picture. Page images never leave your machine.
- [**claude-code-abyss-team**](https://github.com/Suraba03/claude-code-abyss-team) — the setup that built anki_manga, as a template: a lead and two lanes of Claude Code in git worktrees, read-only trainee models, evidence-based done, and model × effort routing that learns from its own ledger.
- **sentence-explainer** — starting: explain any selected sentence on any web page, for learners of popular languages.
- **Next:** an app for climbers (spec stage).

## Day job

**T-Bank, LLM Platform** — LLM Engineer, Jul 2025 – now

- Feature lead for quality monitoring of a real-time anonymization service for personal data (PII) in front of internal LLM apps and AI coding agents: live-traffic sampling at 11M+ events/day, LLM + human annotation, per-entity NER metrics, drift alerts.
- Two-stage LLM annotator (Qwen3-235B on vLLM proposes, a smaller model verifies): precision at 0.8 recall 0.10 → 0.59.
- Data flywheel from monitoring to retraining: detector recall 0.80 → 0.95, precision 0.40 → 0.70.
- Root-caused an ONNX Runtime / Triton serving incident and drove the move to TensorRT: p99 latency −50%. Longformer migration: 3.1× faster, +0.105 recall.
- PII benchmark for AI-coding traffic (Claude Code / Codex): human review cut ~50×.

**Sberbank** — Data Scientist, Model Risk, Jun 2024 – Jun 2025 (Data Science intern from Oct 2023)

- Validated 20+ production models; AutoML challenger pipeline and drift monitoring for ~30 models (−70% manual effort); co-built the bank's first testing framework for LLM and RAG apps, used by 10+ projects.

## Also here

- [**bsc-thesis-ppg-diabetes-hypertension**](https://github.com/Suraba03/bsc-thesis-ppg-diabetes-hypertension) — screening for type 2 diabetes and hypertension from photoplethysmography: wavelet images + VGG / Swin Transformer, Flask demo, English preprint.

## Stack

`Python` · `PyTorch` · `Transformers` · `vLLM` · `Triton` · `ONNX Runtime` · `TensorRT` · `Airflow` · `Kafka` · `SQL` · `JavaScript` · `Chrome MV3` · `Cloudflare Workers` · `Claude Code`

## Contact

[chekmenev031@gmail.com](mailto:chekmenev031@gmail.com) · [LinkedIn](https://www.linkedin.com/in/Suraba03) · [Telegram](https://t.me/suraba03)
