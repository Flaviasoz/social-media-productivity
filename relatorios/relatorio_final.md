# Relatório Final - Análise de Redes Sociais vs Produtividade

**Autor**: [Seu Nome]  
**Data**: [Data de conclusão]  
**Repositório**: [GitHub Project URL]  

---

## 1. Introdução

### 1.1 Contexto
Análise do impacto do uso de redes sociais na produtividade individual, utilizando dados coletados via formulário.

### 1.2 Objetivos
- Identificar correlações entre tempo em redes sociais e produtividade
- Desenvolver modelo preditivo de produtividade
- Sugerir limites saudáveis de uso diário

---

## 2. Metodologia

### 2.1 Fluxo de Trabalho
1. **Coleta**: Dataset do Kaggle ([link](#))
2. **Pré-processamento**:
   - Limpeza de outliers
   - Tratamento de valores faltantes
   - Criação de novas variáveis
3. **Análise Exploratória**:
   - Matriz de correlação
   - Visualizações comparativas
4. **Modelagem**:
   - Regressão Linear
   - Random Forest
   - Validação cruzada

### 2.2 Ferramentas Utilizadas
- Python 3.8
- Jupyter Notebook
- Bibliotecas: Pandas, Scikit-learn, Matplotlib

---

## 3. Resultados

### 3.1 Principais Descobertas
| Métrica | Valor |
|---------|-------|
| Correlação (Redes × Prod.) | -0.52 |
| MAE do Melhor Modelo | 9.8 |
| Limiar Crítico | 2h07min/dia |

### 3.2 Visualizações Chave
![Gráfico de Dispersão](caminho/para/imagem.png)  
*Relação entre horas em redes sociais e produtividade*

---

## 4. Conclusões

### 4.1 Insights
- Uso além de 2h/dia mostra queda acentuada
- Sono adequado atenua efeitos negativos
- Plataformas de vídeo têm maior impacto

### 4.2 Limitações
- Dados auto-reportados
- Amostra limitada (n=1,200)
- Viés demográfico

### 4.3 Próximos Passos
- Coleta de dados objetivos via APIs
- Estudo longitudinal
- Desenvolvimento de app de monitoramento

---

## Anexos

1. [Código Completo](#)
2. [Dataset Processado](#)
3. [Relatório Técnico Detalhado](#)
