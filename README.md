# Supplementary Data - Anonymous Peer Review

This repository contains the supplementary data for the paper submitted for double-blind peer review. 

The data provided here corresponds to the detailed K-Fold cross-validation results of the deep learning models evaluated in the study.

## Files Included

* **`resultados_kfold_segmentacao.csv`**: Contains the per-fold metrics for the instance segmentation task using the evaluated architectures (Nano, Small, Medium).
* **`resultados_kfold_deteccao.csv`**: Contains the per-fold metrics for the object detection task using the same architectures.

## Metrics Legend

Both files follow the same tabular structure:
* **Modelo**: Evaluated architecture (e.g., YOLOv11n, YOLOv26m).
* **Otimizador**: Optimization algorithm used (Adam or MuSGD).
* **Fold**: Partition number from the 5-fold cross-validation.
* **Precisao**: Precision metric.
* **Revocacao**: Recall metric.
* **F1_Score**: Harmonic mean of Precision and Recall.
* **mAP_50**: Mean Average Precision at an IoU threshold of 0.5.
* **mAP_50_95**: Mean Average Precision across IoU thresholds from 0.5 to 0.95.
* **Inferencia_ms**: Inference time per image in milliseconds.
