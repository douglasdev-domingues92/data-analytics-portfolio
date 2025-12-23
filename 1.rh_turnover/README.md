# Predição de Turnover (People Analytics)

## 1. Contexto
A rotatividade de funcionários gera custos diretos (recrutamento, treinamento e onboarding) e custos indiretos, como perda de produtividade, impacto no clima organizacional e perda de conhecimento tácito. Em áreas estratégicas, desligamentos não planejados podem comprometer resultados operacionais e financeiros no curto e médio prazo.

## 2. Problema de Negócio
A área de Recursos Humanos atua majoritariamente de forma reativa, tomando conhecimento do desligamento apenas quando o funcionário formaliza sua saída. Essa abordagem limita a capacidade da empresa de atuar preventivamente em casos de risco elevado de desligamento voluntário.

## 3. Objetivo Analítico
Desenvolver um modelo preditivo capaz de estimar a probabilidade de desligamento voluntário de funcionários ativos, a partir de informações demográficas, funcionais e de engajamento, com o objetivo de apoiar a priorização de ações de retenção.

O modelo não tem finalidade punitiva ou decisória automática, sendo utilizado exclusivamente como ferramenta de apoio à tomada de decisão.

**Pergunta foco: *Dado o perfil atual dos funcionários ativos, quais apresentam maior risco relativo de desligamento, de modo a priorizar ações preventivas de retenção?***

## 4. Uso do Modelo na Tomada de Decisão
Os scores de risco gerados pelo modelo serão utilizados para:
- Priorizar colaboradores para ações de retenção;
- Direcionar esforços de engajamento e acompanhamento gerencial;
- Apoiar decisões de alocação eficiente de recursos de RH.

## 5. Métrica de Sucesso
- **Métricas técnicas**
    - Recall nos percentis de maior risco (ex.: top 10% / 20%);
    - Precision-Recall AUC;
    - Comparação com baseline simples.
- **Indicadores de negócio (proxy)**
    - Capacidade de concentrar esforços de retenção em grupos de maior risco;
    - Redução esperada de custo de turnover, assumindo ações preventivas direcionadas.

## 6. Base de Dados
- **Fonte:** IBM HR Analytics Employee Attrition Dataset (dados públicos e simulados).
- **Descrição:** Dataset contendo informações demográficas, funcionais, de remuneração e satisfação de funcionários.

**Observações importantes:**
- Dataset estático, sem dimensão temporal;
- Riscos associados a data leakage (vazamento de informações);
- Ausência de diferenciação explícita entre desligamento voluntário e involuntário.

Essas limitações são consideradas e discutidas ao longo do projeto.
## 7. Metodologia
- Análise exploratória com foco em hipóteses de negócio;
- Tratamento de variáveis categóricas e numéricas;
- Construção de baseline interpretável;
- Avaliação de modelos supervisionados de classificação;
- Análise de trade-offs entre métricas técnicas e uso prático do modelo.

## 8. Resultados
Seção dedicada à apresentação dos principais resultados:
- Métricas de performance;
- Visualizações relevantes;
- Insights acionáveis para o negócio.

## 9. Limitações e Próximos Passos
- Uso de dados simulados;
- Ausência de histórico temporal;
- Necessidade de validação em dados reais.

Possíveis extensões incluem incorporação de dados temporais, custos explícitos de erro e testes em ambiente produtivo.

## 10. Stack utilizada
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib/Seaborn  
- Jupyter Notebook  
- Power BI (quando aplicável)