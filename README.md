# SpeechNet
Automated deep learning pipeline that classifies audio segments as speech or noise. Built with Python and neural networks, processes spectrograms of thousands of samples and achieves 82% accuracy in speech identification for scalable data curation.




Jupyter notebooks for identifying human speech in audio using feature extraction (STFT, MFCC, Mel-spectrograms) and deep learning models.

## Contents

- `part1.ipynb` — Data loading, feature extraction, and EDA
- `part2.ipynb` — Model building, training, and evaluation

## Usage

1. Clone/download this repo.
2. Put your audio data (WAV files) in a `data/` folder.
3. Install dependencies (`requirements.txt`).
4. Open and run the notebooks in Jupyter or VSCode.

## Requirements

See `requirements.txt` (librosa, tensorflow, matplotlib, pandas, etc.)

## Description

- Classifies audio as speech or not-speech using deep learning.
- Extracts and visualizes signal features for training and model evaluation.

## Observations

- The ANN/CNN achieved an accuracy of approximately 82% in speech classification.
- Spectrogram and MFCC features were crucial for distinguishing speech from music.
- Trimmed audio data improved model consistency and generalization.
- Most misclassifications occurred with noisy samples containing both speech and strong music elements.
- Data augmentation (e.g., noise injection or pitch shift) could further improve results.
