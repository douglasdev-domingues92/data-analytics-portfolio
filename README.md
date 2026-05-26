# Análise de Fatores Associados ao Turnover de Funcionários

Projeto de People Analytics com foco em investigação de fatores associados ao turnover e identificação de grupos com maior risco de desligamento.

O objetivo é transformar dados organizacionais em insights acionáveis para apoiar estratégias de retenção, priorização de ações de RH e tomada de decisão orientada por dados.

---

## Objetivo do Projeto

Responder à seguinte pergunta de negócio:

> Quais fatores parecem mais associados ao turnover e quais grupos deveriam ser priorizados em estratégias de retenção?

A análise busca identificar padrões relacionados a:
- satisfação e engajamento;
- carga de trabalho;
- remuneração;
- crescimento profissional;
- estrutura organizacional.

---

## Contexto de Negócio

Altos níveis de turnover podem gerar impactos relevantes para empresas, como:
- aumento de custos operacionais;
- perda de conhecimento interno;
- redução de produtividade;
- sobrecarga de equipes;
- aumento do tempo de reposição de vagas.

Neste contexto, o projeto investiga possíveis fatores associados ao desligamento de funcionários, com foco em gerar evidências analíticas para apoio à retenção.

---

## Dataset

- IBM HR Analytics Attrition Dataset
- Total de funcionários analisados: 1.470
- Taxa geral de turnover identificada: 16,12%

---

## Principais Hipóteses Investigadas

- Funcionários com horas extras apresentam maior incidência de turnover.
- Funcionários com menor renda mensal apresentam maior taxa de desligamento.
- Áreas com maior pressão operacional podem apresentar maior rotatividade.
- Crescimento profissional e promoções podem influenciar retenção.
- Indicadores de satisfação e equilíbrio vida-trabalho podem estar associados ao turnover.

---

## Tecnologias Utilizadas

- Python
- SQL
- DuckDB
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Estrutura do Projeto

```text
data/
  raw/
  processed/

notebooks/
  01_data_understanding.ipynb
  02_sql_eda.ipynb
  03_python_analysis.ipynb
  04_modeling.ipynb

src/

README.md
```

---

## Etapas da Análise

### 1. Entendimento e preparação dos dados
- tradução e padronização de variáveis;
- remoção de colunas sem valor analítico;
- análise estrutural do dataset.

### 2. Análise exploratória
- turnover por departamento;
- impacto de horas extras;
- turnover por faixa salarial;
- análise de promoções e tempo de empresa;
- segmentações organizacionais.

### 3. Modelagem preditiva
- construção de baseline;
- modelos interpretáveis;
- análise de variáveis relevantes.

### 4. Comunicação de insights
- interpretação executiva;
- recomendações acionáveis;
- limitações da análise.

---

## Principais Aprendizados Esperados

- Construção de análises orientadas a negócio;
- Investigação de fatores organizacionais associados ao turnover;
- Uso combinado de SQL e Python em análises corporativas;
- Desenvolvimento de storytelling analítico;
- Transformação de hipóteses em evidências quantitativas.