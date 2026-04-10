# Chest X-Ray Pneumonia Classifier

> Computer vision pipeline for binary classification
> of chest X-rays — detecting pneumonia with
> EfficientNet-B0 and Grad-CAM explainability.

**Kaggle notebook:** _coming soon_
**Portfolio:** https://cz-light.github.io

---

## Tech stack
- **Framework:** PyTorch · torchvision
- **Model:** EfficientNet-B0 (transfer learning)
- **Augmentation:** Albumentations
- **Explainability:** Grad-CAM
- **Tuning:** Optuna
- **Tracking:** Weights & Biases
- **Platform:** Kaggle Notebooks

---

## Results
| Model | Accuracy | AUC-ROC | Kaggle score |
|---|---|---|---|
| Baseline CNN | — | — | — |
| EfficientNet-B0 | — | — | — |

_Results will be updated as training completes._

---

## Features
- [ ] EDA: class distribution and sample images
- [ ] Baseline CNN from scratch
- [ ] Transfer learning with EfficientNet-B0
- [ ] Data augmentation pipeline (Albumentations)
- [ ] Evaluation: accuracy, AUC-ROC, confusion matrix
- [ ] Grad-CAM saliency map visualizations
- [ ] Kaggle competition submission

---

## Screenshots
_Coming soon_

---

## Local setup
```bash
git clone https://github.com/cz-light/cv-xray-classifier
cd cv-xray-classifier
python -m venv venv
source venv/bin/activate    # Mac/Linux
venv\Scripts\activate       # Windows
pip install -r requirements.txt
```

### Run notebooks
```bash
jupyter notebook
```

---

## Data source
[Chest X-Ray Images (Pneumonia) — Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

---

## Project structure
```
cv-xray-classifier/
├── data/
│   ├── raw/              # original dataset (gitignored)
│   └── processed/        # resized/split data (gitignored)
├── notebooks/            # EDA and training notebooks
├── src/
│   ├── models/           # model architecture definitions
│   └── utils/            # data loaders, transforms, helpers
├── outputs/
│   ├── checkpoints/      # saved model weights (gitignored)
│   └── figures/          # training curves, Grad-CAM images
└── docs/
    └── screenshots/
```

---

## What I learned
_To be written on project completion._