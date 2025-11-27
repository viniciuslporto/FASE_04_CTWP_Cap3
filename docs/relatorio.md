# Relatório Técnico - Classificação de Grãos de Trigo

## 1. Entendimento do Negócio

O projeto visa automatizar a classificação de grãos de trigo em cooperativas agrícolas, reduzindo tempo e erros humanos no processo manual.

## 2. Entendimento dos Dados

- Dataset: 210 amostras, 7 features, 3 classes balanceadas
- Sem valores ausentes
- Features numéricas contínuas (medidas físicas)

## 3. Preparação dos Dados

- Padronização com StandardScaler
- Divisão estratificada 70/30
- Validação cruzada 5-fold

## 4. Modelagem

Algoritmos testados:
- KNN
- SVM
- Random Forest
- Naive Bayes
- Logistic Regression

## 5. Avaliação

Métricas utilizadas:
- Acurácia
- Precisão
- Recall
- F1-Score
- Matriz de Confusão

## 6. Implantação

O modelo pode ser integrado a sistemas de visão computacional para classificação automática em tempo real.
```

4. Clique em **"Commit new file"**

---

### **PASSO 8: Estrutura final do repositório**

Seu repositório deve ficar assim:
```
FASE_04_CTWP_Cap3/
├── assets/
│   └── logo-fiap.png
├── data/
│   └── seeds_dataset.txt
├── notebooks/
│   └── seeds_classification_v2.ipynb
├── docs/
│   └── relatorio.md
├── README.md
└── requirements.txt
