# O2-fluctuation-ROP-Models

This work has been published in the journal `Ophthalmology Science` [Oxygenation Fluctuations Associated with Severe Retinopathy of Prematurity: Insights from A Multimodal Deep Learning Approach](https://www.ophthalmologyscience.org/article/S2666-9145(23)00149-5/fulltext). This repository contains a Jupyter notebook that focuses on the development and evaluation of ML and deep learning models for severe ROP prediction.

## Overview

ROP is a potentially blinding eye disorder that primarily affects premature infants. This project aims to leverage diverse data types to enhance prediction accuracy and provide insights into the factors influencing ROP.

The `ROP_O2_ML_model` notebook covers the following steps:
- Data import and preprocessing
- Feature selection using Recursive Feature Elimination (RFE)
- Model development and evaluation with Random Forest and Support Vector Machine (SVM)
- 5-Fold Cross-Validation and result visualization

The `Multimodal_O2_model` notebook covers the following steps:
- Data preprocessing for both static and time-series data.
- LSTM-based neural network model for time-series data processing.
- Integration of static and time-series data for prediction.
- Comprehensive evaluation metrics including accuracy, F1 score, and ROC AUC.

## Requirements

To run the notebook, you'll need:
- Python 3.10
- Jupyter Notebook
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn
- PyTorch 1.12.1

## Usage

1. Clone this repository or download the files.
2. Install the required libraries.
3. Open and run the notebook.

## License

This project is open-sourced under the MIT License. See `LICENSE` for more details.

## Contributing

Pull requests are welcome. 

