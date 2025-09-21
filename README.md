# Medical Image Triage Assistant

Prototype to prioritize medical images (e.g., chest X-rays) by flagging likely abnormal scans for faster human review. **For research/education only — not for clinical use.**

## What’s included
- `src/dataset.py` — simple image loader
- `src/model.py` — small CNN (PyTorch)
- `src/train.py` — training script (example uses dummy labels; replace with real labeled dataset)
- `src/infer.py` — inference that outputs `abnormal_prob` and `flag` per image

## Quickstart
1. Create venv and install:
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
