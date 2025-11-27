# FASE_04_CTWP_Cap3
# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Classificação de Variedades de Grãos de Trigo

## 👨‍🎓 Integrantes: 
-Vinicius de Santana Gama - RM566672
-Pedro Carvalho Rocha Lima - RM567330
- Vinicius Lisboa Porto - RM561406
- Marlon Paulino Marinho - RM566793
- Danilo Marques Dantas - RM567583

## 👩‍🏫 Professores:
### Tutor(a) 
- Lucas Gomes Moreira
### Coordenador(a)
- André Godoi Chiovato

## 📜 Descrição

Este projeto aplica a metodologia **CRISP-DM** para desenvolver modelos de Machine Learning capazes de classificar automaticamente três variedades de trigo (Kama, Rosa e Canadian) com base em características físicas dos grãos.

### Contexto do Problema
Em cooperativas agrícolas de pequeno porte, a classificação manual de grãos é demorada e sujeita a erros humanos. Este projeto visa automatizar esse processo através de algoritmos de aprendizado de máquina, aumentando eficiência e precisão.

### Objetivos
- Analisar e pré-processar o Seeds Dataset (UCI Machine Learning Repository)
- Implementar e comparar 5 algoritmos de classificação
- Otimizar modelos através de GridSearchCV
- Interpretar resultados e extrair insights para aplicação prática

### Dataset
- **Fonte**: UCI Machine Learning Repository - Seeds Dataset
- **Amostras**: 210 grãos (70 de cada variedade)
- **Features**: 7 características físicas (área, perímetro, compacidade, etc.)
- **Classes**: 3 variedades (Kama, Rosa, Canadian)

### Metodologia
- **Framework**: CRISP-DM (Cross Industry Standard Process for Data Mining)
- **Algoritmos testados**: 
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Random Forest
  - Naive Bayes
  - Logistic Regression
- **Técnicas aplicadas**:
  - Análise exploratória completa
  - Padronização de features (StandardScaler)
  - Validação cruzada estratificada (5-fold)
  - Otimização de hiperparâmetros (GridSearchCV)
  - Feature importance analysis

### Resultados Esperados
- Acurácia superior a 90% na classificação
- Identificação das features mais importantes
- Modelo pronto para aplicação em cooperativas agrícolas

## 📁 Estrutura de pastas
```
FASE_04_CTWP_Cap3/
│
├── assets/                      # Imagens e recursos
│   └── logo-fiap.png
│
├── data/                        # Datasets
│   └── seeds_dataset.txt
│
├── notebooks/                   # Notebooks Jupyter
│   └── seeds_classification_v2.ipynb
│
├── docs/                        # Documentação adicional
│   └── relatorio.md
│
├── README.md                    # Este arquivo
└── requirements.txt             # Dependências do projeto
```

## 🔧 Como executar o código

### Pré-requisitos
- Python 3.8 ou superior
- Jupyter Notebook ou Google Colab

### Instalação de dependências
```bash
pip install -r requirements.txt
```

### Execução

#### Opção 1: Google Colab (Recomendado)
1. Abra o arquivo `notebooks/seeds_classification_v2.ipynb` no Google Colab
2. Faça upload do arquivo `data/seeds_dataset.txt`
3. Execute todas as células: **Ambiente de execução** → **Executar tudo**

#### Opção 2: Jupyter Local
1. Clone o repositório
2. Navegue até a pasta do projeto
3. Execute: `jupyter notebook`
4. Abra o arquivo `notebooks/seeds_classification_v2.ipynb`
5. Execute todas as células

## 🗃 Histórico de lançamentos

* 1.0.0 - 27/11/2024
    * Versão inicial do projeto
    * Implementação completa da metodologia CRISP-DM
    * 5 algoritmos de classificação implementados e otimizados
    * Análise exploratória e visualizações completas

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
