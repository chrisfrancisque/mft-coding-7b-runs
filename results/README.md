# Experiment Results (summaries)

This folder captures **small artifacts** only (metrics + logs). Full checkpoints are excluded.

- `base/metrics.json` — LLaMA-2-7B (no FT)
- `fft/metrics.json` — Fully fine-tuned
- `mft/metrics.json` — Mask fine-tuned (layers 20–23, keep≈0.9)

See `logs/` for training/eval logs.
