# Spatio-Temporal Heatwave Detection using Deep Learning

## Overview

This project predicts heatwave events using ERA5 climate reanalysis data and a ResNet-34 deep learning model. The model learns spatio-temporal patterns from meteorological variables to classify whether a heatwave will occur.

## Features

- ERA5 climate dataset
- Time-series preprocessing
- Spatial feature extraction
- ResNet-34 based binary classification
- PyTorch implementation
- Model evaluation using ROC-AUC

## Dataset

The project uses ERA5 climate reanalysis data obtained from the Copernicus Climate Data Store.

**Variables used**
- Temperature
- Dew Point
- Surface Pressure
- Wind Components

> Due to dataset size, the raw ERA5 files are not included in this repository.

## Technologies

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
## Results

### Training vs Validation Loss

![Training Loss](training_validation_loss.png)

### ROC Curve

![ROC Curve](roc_curve.png)

### F1-score vs Threshold

![F1 Threshold](f1_threshold_curve.png)

### Final Performance

| Metric | Value |
|---------|------:|
| Accuracy | 0.8395 |
| Precision | 0.6355 |
| Recall | 1.0000 |
| F1-score | 0.7771 |
| ROC-AUC | **0.9466** |
| Brier Score | 0.1140 |

![Evaluation Metrics](evaluation_metrics.png)

## Repository Structure

```
heatwave_prediction.ipynb
README.md
```

## Author

Jenifer Treesa Joseph
