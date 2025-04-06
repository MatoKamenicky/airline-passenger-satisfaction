# Airline Passenger Satisfaction – MLP Classifier (Google Colab)

This project uses a Multi-Layer Perceptron (MLP) neural network to predict airline passenger satisfaction from tabular data, trained and visualized in a Jupyter Notebook on Google Colab.

## 📊 Dataset

- **Source**: [Kaggle – Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)
- Data includes features such as seat comfort, flight distance, delays, and onboard services
- Binary classification: `Satisfied` vs `Neutral or Dissatisfied`

## 🧠 Model

- **Architecture**: Multi-Layer Perceptron (MLP) using PyTorch
- Input preprocessing: label encoding, feature scaling
- Model evaluation: accuracy, F1-score

## 🛠 Technologies Used

- Google Colab (Python 3, Jupyter Notebook)
- PyTorch
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 🚀 How to Run

You can open and run the notebook in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/your-notebook-link-here)

Or clone this repository and run locally:

```bash
git clone https://github.com/your-username/airline-satisfaction-mlp.git
cd airline-satisfaction-mlp
jupyter notebook

## 📈 Results

- **Achieved accuracy**: ~96,5%
- **Achieved F1 score**: ~95,9%