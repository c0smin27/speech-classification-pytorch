# Speech Classification from Scratch

## Description

This project implements a speech classification system using the **X-vector architecture**, following the **SpeechBrain** methodology. The model extracts speaker embeddings and classifies audio signals. The system was trained on a dataset of **1519 audio files** from **28 speakers**. The entire pipeline, from data preparation (JSON generation) to final evaluation, was executed in **Google Colab**.

**❗❗ To view the complete project, including source code, detailed training logs, and t-SNE visualizations, download the `Speech Classification from Scratch.html` file and open it locally in a web browser. ❗❗**

## Technical Details and Dataset

- **Dataset**: 1519 audio samples, divided into:
  - **Train**: 1050 files
  - **Validation**: 215 files
  - **Test**: 254 files
- **Architecture**: X-vector topology for robust feature extraction.
- **Hardware**: Executed on an NVIDIA GeForce RTX 3060 Laptop GPU.

## Model Results

The following performance metrics were obtained on the test set after the training process:

| Metric | Value |
|--------|-------|
| **Best Validation Accuracy** | 99.07% |
| **Final Test Accuracy** | 98.43% |
| **Total Test Errors** | 4 / 254 |
| **Macro-averaged EER (Equal Error Rate)** | 0.13% |

## Technologies Used

- Python (**Google Colab**)
- PyTorch / SpeechBrain
- Jupyter Notebook
- Matplotlib / Scikit-learn (for embedding visualization)

## Project Files

- `Speech Classification from Scratch.ipynb` - main implementation notebook
- `Speech Classification from Scratch.html` - complete report with results and graphs

## Disclaimer

This project was created as part of an academic assignment. Feel free to use it for learning purposes, but please do not submit it as your own work in educational settings.
