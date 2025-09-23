# Separate-and-Detect — Audio Demo Page

Live page: https://ddman1101.github.io/dssdtm.github.io/

This demo page showcases our separation-then-transcription pipeline for automatic drum transcription (ADT). It contains:

- Abstract: a short overview of the task and method.
- Pianoroll + Six‑track Audios (Two examples):
  - For each example: one pianoroll image.
  - Four 6‑audio sets per example: Target, Prediction—ADTOF, Prediction—LarsNet, Prediction—MSG‑LD (+OB & TB).
  - Each set includes Mixture + the five stems above.

All audio files and images are under `assets/` (see `assets/audio/` for clips). Replace the placeholder files with your own to customize the page.

### Data note
The drum sounds in our examples are rendered from one-shot samples extracted from the StemGMD dataset.
