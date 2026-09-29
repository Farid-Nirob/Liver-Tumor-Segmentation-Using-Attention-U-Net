# Liver Tumor Segmentation Using Attention U-Net

A deep learning project for automated liver and tumor segmentation from CT images using the Attention U-Net architecture and the LiTS dataset.

## Overview

Accurate segmentation of the liver and liver tumors from CT scans is an important task in medical image analysis. This project explores the use of Attention U-Net for automatically identifying and segmenting liver and tumor regions from CT images.

The attention mechanism helps the network focus on relevant anatomical regions while suppressing less useful features during segmentation.

## Dataset

This project uses a prepared train/validation version of the **LiTS (Liver Tumor Segmentation) dataset** hosted on Kaggle.

**Dataset:** [LiTS Train-Val - Kaggle](https://www.kaggle.com/datasets/javariatahir/litstrain-val)

The dataset contains abdominal CT imaging data and corresponding segmentation masks used for training and evaluating the liver and tumor segmentation model.

## Model

The segmentation model is based on **Attention U-Net**, an extension of the U-Net architecture that incorporates attention gates to improve feature selection during segmentation.

## Repository Structure

Liver-Tumor-Segmentation-Using-Attention-U-Net/
|
|-- notebooks/
|   -- attention-unet-lits-kaggle.ipynb
|
|-- docs/
|   -- Liver Tumor Segmentation Using Attention U-Net.pdf
|
|-- result/
|   -- summery-poster.pptx
|
|-- README.md

## Implementation

The current implementation is provided as a Jupyter Notebook and was developed and executed using Kaggle.

The notebook contains the current data processing, model implementation, training, evaluation, and visualization workflow.

## Results

Experimental results and visualizations are available in the notebook. Additional documentation and a summary poster are included in the repository.

## Future Work

The repository will continue to be updated with improvements to the code structure, documentation, evaluation, and segmentation pipeline.

