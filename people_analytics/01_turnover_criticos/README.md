# People Analytics — Turnover Crítico em Instituição Financeira

**Área:** People Analytics  
**Setor:** Financeiro

---

## Problema de Negócio

Um banco nacional fictício (aproximadamente 2.500 colaboradores) apresenta sinais claros de deterioração organizacional em áreas críticas, principalmente **Comercial** e **Tecnologia**.

Foram identificados:

- Aumento consistente da rotatividade de colaboradores
- Crescimento do custo de reposição e impacto na produtividade
- Queda no engajamento, especialmente nos últimos 12 meses
- Indícios de desigualdade em promoções entre grupos
- Demora na reposição de talentos estratégicos

Esses fatores impactam diretamente indicadores de negócio, como:

- Aquisição de clientes
- Eficiência operacional
- Qualidade das entregas
- Risco de perda de conhecimento crítico

**Oportunidade estratégica**

Criar uma base analítica robusta (simulada) para:

- compreender os fatores que impulsionam desligamentos
- priorizar ações de retenção
- estimar o impacto financeiro de diferentes cenários de decisão

---

## Objetivos do Projeto

### Objetivo Principal

Investigar e explicar os fatores que impulsionam a saída de colaboradores em áreas críticas, além de estruturar um modelo de risco e recomendações executivas orientadas a impacto.

### Objetivos Secundários

- Construir uma base simulada realista com problemas típicos de People Analytics
- Aplicar análise exploratória orientada a hipóteses
- Conduzir testes de causalidade e significância estatística
- Criar indicadores estratégicos e estimar impacto financeiro
- Desenvolver um modelo preditivo simples
- Elaborar um plano executivo de ações com análise de retorno
- Produzir documentação profissional e reprodutível

---

## Abordagem Analítica

### 1. Formulação do problema e hipóteses

Perguntas que orientam a análise:

- Quais variáveis antecedem o desligamento de colaboradores?
- Existe algum tipo de viés na gestão de promoções e talentos?
- O custo de reposição está acima do esperado?
- A queda de engajamento contribui para o aumento da rotatividade?

---

### 2. Estrutura Analítica

Principais relações investigadas:

Engajamento → Performance → Promoção → Risco de Saída  

Carga de Trabalho → Bem-estar → Absenteísmo → Risco de Saída  

Compa Ratio → Equidade Salarial → Retenção

---

### 3. Execução Técnica

Ferramentas utilizadas:

- Python
- Pandas
- SciPy
- Scikit-learn

Características do projeto:

- Base de dados **100% reproduzível**
- Controle de aleatoriedade (seed)
- Análises e visualizações orientadas à tomada de decisão
- Documentação estruturada para uso em portfólio e reprodutibilidade

---

## Estrutura do Repositório

```
01_turnover_critico/
│
├── data/
│   ├── raw/                 # Dados simulados brutos gerados por código
│   └── processed/           # Dados tratados para análise
│
├── notebooks/
│   ├── 01_data_generation.ipynb
│   ├── 02_qualidade_tratamento.ipynb
│   ├── 03_analise_exploratoria.ipynb
│   ├── 04_testes_hipoteses.ipynb
│   ├── 05_indicadores_financeiros.ipynb
│   ├── 06_modelo_preditivo.ipynb
│   └── 07_recomendacoes_executivas.ipynb
│
├── outputs/
│   ├── reports/          # Gráficos, tabelas e resultados das análises
│   └── models/           # Artefatos de modelos treinados
│
├── src/
│   ├── data/               # Funções para geração e tratamento de dados
│   ├── analysis/           # Funções de análise exploratória e testes
│   ├── modeling/           # Código relacionado aos modelos preditivos
│   └── utils/              # Funções auxiliares e configurações
│
└── README.md
```

---

## Resultados Esperados

- Identificação dos principais fatores associados à rotatividade
- Quantificação do impacto financeiro do turnover
- Modelo simples de risco de saída de colaboradores
- Recomendações estratégicas para retenção de talentos

---

## Aplicação do Projeto

Este projeto simula um caso real de **People Analytics aplicado ao setor financeiro**, demonstrando como análise de dados pode apoiar decisões estratégicas relacionadas a:

- gestão de talentos
- retenção de profissionais críticos
- eficiência organizacional
- sustentabilidade do capital humano
