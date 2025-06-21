# Requerimentos do Projeto - Limpeza de Dados 

Este projeto utiliza as seguintes bibliotecas Python para limpeza e preparação dos dados:

- `pandas` – Manipulação e análise de dados  
- `numpy` – Operações numéricas e vetoriais  
- `matplotlib` – Visualização de dados  
- `seaborn` – Visualização estatística  
- `kagglehub` – Acesso a datasets do Kaggle  

# Requerimentos do Projeto - Análise Exploratória

Este projeto utiliza as seguintes bibliotecas Python para análise estatística e geração de relatório:

- `scipy` – Cálculos estatísticos e testes de hipótese  
- `weasyprint` – Geração de PDF a partir de HTML/CSS  
- `pdfkit` – Alternativa para geração de PDFs com suporte ao `wkhtmltopdf`  
- `google.colab` – Integrações para download e execução no ambiente Colab  
- `nbconvert` / `nbformat` – Exportação de notebooks em HTML (caso necessário)  

# Requerimentos do Projeto - Modelagem

Este projeto utiliza as seguintes bibliotecas Python para modelagem e avaliação de desempenho:

- `scikit-learn` – Treinamento, avaliação e validação de modelos  
  - `train_test_split`, `cross_val_score` – Divisão e validação cruzada  
  - `StandardScaler` – Normalização dos dados  
  - `LinearRegression`, `RandomForestRegressor`, `SVR` – Modelos de regressão  
  - `mean_absolute_error`, `r2_score` – Métricas de avaliação  
- `xgboost` – Implementação eficiente de gradient boosting  

# Instalação de dependências no Google Colab

```python
!pip install -q kagglehub pdfkit weasyprint xgboost scikit-learn
!apt-get update && apt-get install -y wkhtmltopdf
```

# Imports utilizados no notebook

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import mean_absolute_error, r2_score
from sklearn.linear_model import LinearRegression
from sklearn.ensemble import RandomForestRegressor
from sklearn.svm import SVR
import xgboost as xgb
import warnings
import os
import requests
from io import StringIO
import matplotlib.ticker as mtick
from weasyprint import HTML
import datetime
from google.colab import files

warnings.filterwarnings('ignore')
plt.style.use('seaborn-v0_8-whitegrid')
%matplotlib inline
os.makedirs("imgs_temp", exist_ok=True)
```
