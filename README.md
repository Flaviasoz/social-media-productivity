# Análise de Redes Sociais vs Produtividade

## Visão Geral do Projeto

Este projeto investiga a relação entre o uso de redes sociais e a produtividade pessoal utilizando técnicas de ciência de dados. A análise segue um fluxo completo de trabalho, desde a definição do problema até a implantação do modelo.

## Conjunto de Dados

**Fonte**: [Kaggle - Social Media vs Productivity Dataset](https://www.kaggle.com/datasets/mahdimashayekhi/social-media-vs-productivity)

**Variáveis Principais**:
- Informações demográficas (idade, gênero)
- Métricas de uso de redes sociais (horas diárias, plataformas utilizadas)
- Autoavaliação de produtividade (escala 0-100)
- Fatores de estilo de vida (horas de sono, níveis de estresse)

## Estrutura do Projeto
```bash
/social-media-productivity
│── /dados # Arquivos de dados
│ ├── dados_brutos.csv # Dataset original
│ └── dados_processados.csv # Dados limpos e transformados
│── /notebooks # Jupyter notebooks para cada fase
│ ├── 1_limpeza_dados.ipynb
│ ├── 2_analise_exploratoria.ipynb
│ └── 3_modelagem.ipynb
│── /relatorios # Documentação do projeto
│ ├── relatorio_final.md
│ └── relatorio_final.pdf
│── requirements.txt # Dependências Python
└── README.md # Este arquivo
```


## Principais Resultados

1. Correlação negativa (-0.52) entre uso de redes sociais e produtividade
2. Limiar crítico em ~2 horas/dia de uso de redes sociais
3. Qualidade do sono surgiu como fator significativo
4. Modelo Random Forest obteve melhor desempenho (MAE = 9.8)

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seuusuario/social-media-productivity.git
```

2. Instale as dependências:
pip install -r requirements.txt

## Como Usar
Execute os notebooks em sequência:

1. limpeza_dados.ipynb

2. analise_exploratoria.ipynb

3. modelagem.ipynb

## Dependências

* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* jupyter

## Contribuidores
198726 - Flávia Souza
198779 - Vinicius Loeblein

## Agradecimentos
* Fornecedor do dataset: Mahdi Mashayekhi
* Inspiração: Estudos sobre bem-estar digital
