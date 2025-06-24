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
│── /data # Arquivos de dados
│ ├── processed_data.csv
│ └── social_media_vs_productivity.csv
│── /notebooks # notebooks para cada fase
│ ├── analise_exploratoria.ipynb
│ ├── limpeza_dados.ipynb 
│ └── modelagem.ipynb
│── /relatorios
│ ├── plano_de_aula.pdf
│ ├── rel_analise_exploratoria.pdf
│ ├── rel_limpeza_dados.pdf
│ └── rel_modelagem.pdf
│── README.md # Este arquivo
└── requirements.md # Dependências do projeto
```

## Instalação

 Clone o repositório:
```bash
git clone https://github.com/Flaviasoz/social-media-productivity.git
```

## Como Usar
Execute os notebooks em sequência:

1. limpeza_dados.ipynb

2. analise_exploratoria.ipynb

3. modelagem.ipynb

## Contribuidores
* 198726 - Flávia Souza
* 198779 - Vinicius Loeblein

## Agradecimentos
* Fornecedor do dataset: Mahdi Mashayekhi
* Inspiração: Estudos sobre bem-estar digital
