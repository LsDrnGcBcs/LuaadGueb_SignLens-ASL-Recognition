# SignLens: ASL Recognition using CNN-LSTM

## Overview
This project implements a CNN-LSTM model for recognizing 10 American Sign Language (ASL) words from video sequences using the WLASL dataset.

## Features
- Video preprocessing (frame extraction, resizing, normalization)
- CNN-LSTM architecture
- Early stopping
- Performance evaluation (accuracy, F1-score)

## Dataset
WLASL v0.3 dataset (subset of 10 words)

## Model
- TimeDistributed CNN for spatial features
- LSTM for temporal modeling
- Dense layers for classification

## Results
The model achieved limited performance due to small dataset size and class similarity, with only a few classes reaching non-zero F1-scores.

## Authors
[Your names]
