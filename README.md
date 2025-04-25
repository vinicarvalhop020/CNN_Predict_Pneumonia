# CNN_Predict_Pneumonia

# Detecção de Pneumonia em Raios-X com CNN em PyTorch

## 📌 Visão Geral
Projeto de deep learning utilizando PyTorch para classificação automática de pneumonia em imagens de radiografia torácica. O modelo CNN foi desenvolvido para auxiliar no diagnóstico médico, classificando imagens como "Normal" ou "Pneumonia".

## 🗃️ Conjunto de Dados
A base de dados utilizada foi [Chest X-Ray Images (Pneumonia) dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) do Kaggle contendo:

- **5,800 imagens** (treino/validação/teste)

## 🏗️ Estrutura do Projeto
pneumonia-cnn/
├── data/
│ ├── train/
│ │ ├── NORMAL/
│ │ └── PNEUMONIA/
│ ├── test/
│ └── val/
├── models/
│ ├── model.py
│ └── best_model.pth
├── notebooks/
│ ├── exploratory_analysis.ipynb
│ └── model_training.ipynb
├── src/
│ ├── data_preprocessing.py
│ ├── train.py
│ └── predict.py
├── requirements.txt
└── README.md

📊 Resultados
Métrica	Valor
Acurácia	92.3%
Precisão	93.1%
Recall	91.8%
F1-Score	92.4%

![Matriz de Confusão](docs/confusion_matrix.png)

