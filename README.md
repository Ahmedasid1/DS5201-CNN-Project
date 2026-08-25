# DS5201-CNN-Project

Deep Learning Project 2: **CNNs from Scratch vs Transfer Learning** for image classification.

## Repository Contents

- `DS5201_CNN_Project2.ipynb` — complete implementation for Tasks 1–7
- `requirements.txt` — Python dependencies
- `TECHNICAL_REPORT_TEMPLATE.md` — 13-section report template

## What the notebook includes

The notebook implements:
1. Dataset selection and exploration (CIFAR-100 subset, 10 classes)
2. Data preprocessing and train/validation/test split (70/15/15)
3. Data augmentation (flip, rotation, zoom, translation, contrast)
4. CNN model from scratch
5. Transfer learning with MobileNetV2 (frozen base)
6. Fine-tuning of upper MobileNetV2 layers
7. Experimental comparison with metrics, curves, confusion matrix, and misclassified images

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run

```bash
jupyter notebook DS5201_CNN_Project2.ipynb
```

## Notes

- Random seeds are fixed for reproducibility.
- You can reduce runtime using `MAX_TRAIN_SAMPLES`, `MAX_VAL_SAMPLES`, and `MAX_TEST_SAMPLES` in the notebook config cell.
- The notebook writes `comparison_results.csv` after training/evaluation for report use.

## Technical Report

Use `TECHNICAL_REPORT_TEMPLATE.md` to write your final report and export to PDF for submission.
