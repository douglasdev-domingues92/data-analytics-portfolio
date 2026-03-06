# People Analytics — Turnover Crítico em Instituição Financeira
**Área: People Analytics | Setor Financeiro**

## 🏦 Problema de Negócio

Um banco nacional fictício (aproximadamente 2.500 colaboradores) enfrenta sinais claros de deterioração organizacional em áreas críticas — Comercial e Tecnologia. 

Foram identificados:

- Aumento consistente do turnover
- Custo de reposição crescente e pressão sobre produtividade
- Engajamento em queda, especialmente nos últimos 12 meses
- Indícios de desigualdade em promoções entre grupos
- Atraso na reposição de talentos estratégicos

Esses elementos impactam diretamente indicadores de negócio como aquisição de clientes, eficiência operacional, qualidade de entrega e risco de perda de conhecimento crítico.

**Oportunidade estratégica:**
Criar uma base analítica robusta (mesmo que simulada) para compreender drivers de saída, priorizar ações de retenção e estimar o impacto financeiro de cenários de decisão.

---

## 🎯 Objetivos do Projeto

**Objetivo Principal**:
Investigar e explicar os fatores que impulsionam o turnover em áreas críticas, além de estruturar um modelo de risco e recomendações executivas orientadas a impacto.

**Objetivos Secundários**:

- Construir base simulada realista, com problemas estruturais típicos de People Analytics
- Aplicar análise exploratória orientada a hipóteses
- Conduzir testes de causalidade e significância estatística
- Criar indicadores estratégicos e medir impacto financeiro
- Desenvolver um modelo preditivo simples (baseline)
- Gerar plano executivo de ações, com análise de ROI
- Entregar documentação profissional e reprodutível

---

## 🧠 Abordagem Analítica

**1. Desenho do problema e hipóteses**

- Quais variáveis antecedem o desligamento?
- Há injustiça ou enviesamento na gestão de talentos?
- O custo de reposição é maior do que o esperado?
- A queda de engajamento explica parte do aumento do turnover?

**2. Funil Analítico / Driver Tree**

- Engagement → Performance → Promoção → Risco de Saída
- Workload → Well‑being → Absenteísmo → Risco de Saída
- Compa Ratio → Equidade → Retenção

**3. Execução Técnica**

- Python + Pandas + SciPy + Scikit-learn
- Dataset 100% reproduzível (seed control)
- Análises e gráficos orientados a decisão executiva
- Documentação clara para GitHub

---

## 🗂 Estrutura do Repositório

01_turnover_criticos/
│
├── data/
│   ├── raw/          # Dados simulados brutos (gerados por código)
│   ├── processed/    # Dados tratados e enriquecidos para análise
│
├── notebooks/
│   ├── 01_data_generation.ipynb
│   ├── 02_data_quality.ipynb
│   ├── 03_eda_strategica.ipynb
│   ├── 04_testes_hipoteses.ipynb
│   ├── 05_indicadores_financeiros.ipynb
│   ├── 06_modelo_preditivo.ipynb
│   └── 07_recomendacoes_executivas.ipynb
│
├── outputs/
│   ├── reports/      # Gráficos, tabelas, dashboards estáticos
│   └── models/       # Modelos e artefatos (picles se necessário)
│
├── src/
│   ├── data/         # Funções para gerar/tratar dados
│   ├── analysis/     # Funções de EDA, testes e indicadores
│   ├── modeling/     # Scripts de modelagem
│   └── utils/        # Helper functions, configs
│
└── README.md
