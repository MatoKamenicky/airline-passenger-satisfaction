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

## 📈 Results

- **Achieved accuracy**: ~96,5%
- **Achieved F1 score**: ~95,9%

## 🚀 How to Run

You can open and run the notebook in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MatoKamenicky/airline-passenger-satisfaction/blob/main/Airline_Satisfaction_MLP.ipynb)

Or clone this repository and run locally:

```bash
git clone https://github.com/MatoKamenicky/airline-passenger-satisfaction.git
cd airline-passenger-satisfaction
jupyter notebook
