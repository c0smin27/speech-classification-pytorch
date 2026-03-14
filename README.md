# Speech Classification from Scratch

## Description

This project implements a speech classification system using the **X-vector architecture**, following the **SpeechBrain** methodology. It focuses on extracting robust speaker embeddings and classifying audio signals from scratch. The entire development, from data preparation to model evaluation, was performed in **Google Colab**.

**❗❗ To view the complete project, including code, training logs, and visualizations, download the `Speech Classification from Scratch.html` file and open it locally in any web browser. ❗❗**

## How the Model Works

1. **Environment Setup**: Configuration for local or Colab execution, including mounting Google Drive and installing dependencies like `speechbrain`.
2. **Data Processing**: Preparation of audio signals and feature extraction for the X-vector model.
3. **Architecture**: Implementation of the X-vector topology, known for its efficiency in capturing speaker-specific characteristics.
4. **Integration**: The project uses specialized scripts to export the notebook into a standalone HTML report.

## Technologies Used

- Python (**Google Colab**)
- PyTorch
- SpeechBrain
- Jupyter Notebook

## Model Results

| Metric | Value |
|-------|-------|
| **Training Loss** | 0.0415 |
| **Validation Loss** | 0.4385 |
| **Test Error Rate** | 12.35% |

## Project Files

- `Speech Classification from Scratch.ipynb` - main implementation notebook
- `Speech Classification from Scratch.html` - exported results and visualizations

## Disclaimer

This project was created as part of an academic assignment. Feel free to use it for learning purposes, but please do not submit it as your own work in educational settings.
