# DINOv2 Product Classifier

Testing DINOv2 (Meta, 2023) on product classification. Frozen ViT-S/14 backbone with a linear head. 95.7% test accuracy across 30 classes in 10 epochs.

## Dataset

[Fashion Product Images (Small)](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small) — Kaggle. Download and place as:

```
data/
  images/
  styles.csv
```

## Setup

```bash
pip install torch torchvision transformers scikit-learn pandas matplotlib seaborn pillow
```

## Run

Open `DINOv2_classification.ipynb` and run all cells.
