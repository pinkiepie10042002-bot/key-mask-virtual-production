# key-mask-virtual-production
Dataset, source code and experimental results for machine-learning-based key-mask generation in virtual media production.
# Dataset, Source Code and Results for Key-Mask Generation in Virtual Media Production

This repository contains supplementary materials for the scientific article:

**Study of the Applicability of Machine Learning Models for Object Tracking to Virtual Production of Media Content**

Author: Vladislav M. Molchanov

## Description

The repository includes the dataset, source code, trained model results and experimental metrics used for comparing machine learning models for automatic key-mask generation in virtual media production.

The experiment compares the following segmentation models:

- YOLO-seg
- U-Net
- DeepLabV3
- Detectron2 Mask R-CNN

The models were evaluated using PSNR, Dice and IoU metrics on a dataset of 63 images formed as 7 objects combined with 9 backgrounds.

## Repository structure

- `dataset/` — input images and reference binary masks;
- `results/` — visual comparisons, training graphs, heat maps and metric tables;
- `src/` — source code for training and evaluation;
- `requirements.txt` — Python dependencies.

## Metrics

The main evaluation metrics are:

- PSNR
- Dice coefficient
- IoU / Jaccard index

## Citation

Molchanov V.M. Dataset, source code, trained models and comparison results for key-mask generation in virtual media production.

## License

Materials are provided for research and educational purposes.
