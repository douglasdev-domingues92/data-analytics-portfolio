# Sistema de Retenção de Talentos (People Analytics)

## 1. Contexto
A rotatividade de colaboradores gera custos diretos (recrutamento, treinamento e onboarding) e custos indiretos, como perda de produtividade, impacto no clima organizacional e perda de conhecimento tácito. Em funções críticas, desligamentos não planejados podem comprometer resultados operacionais e financeiros no curto e médio prazo.

Nesse contexto, iniciativas de retenção tendem a ser mais eficazes quando direcionadas de forma priorizada, considerando risco, impacto e capacidade de atuação da gestão.

## 2. Problema de Negócio
A área de Recursos Humanos e as lideranças costumam atuar de forma reativa, tomando conhecimento do desligamento apenas quando o colaborador formaliza sua saída. Essa abordagem limita a capacidade da organização de atuar preventivamente e de alocar recursos de retenção de forma eficiente.

Além disso, decisões de retenção frequentemente não consideram o impacto financeiro associado ao turnover, dificultando a priorização entre diferentes casos e áreas.

## 3. Objetivo Analítico
Desenvolver um sistema analítico de apoio à decisão capaz de:
- Estimar o risco relativo de desligamento voluntário de colaboradores ativos;
- Identificar os principais fatores associados ao turnover;
- Estimar o impacto financeiro potencial da rotatividade.

O sistema não tem finalidade punitiva ou decisória automática, sendo utilizado exclusivamente como suporte à tomada de decisão gerencial.

**Pergunta foco:**  
*Dado o perfil atual dos colaboradores, quais apresentam maior risco e maior impacto potencial de desligamento, de modo a priorizar ações preventivas de retenção?*

## 4. Uso do Sistema na Tomada de Decisão
Os outputs do sistema serão utilizados para:
- Priorizar colaboradores e áreas para ações de retenção;
- Apoiar gestores no acompanhamento de casos de maior risco;
- Direcionar investimentos de engajamento e desenvolvimento;
- Apoiar discussões estratégicas sobre custo e impacto do turnover.

## 5. Métricas de Sucesso
- **Métricas técnicas**
  - Recall nos percentis de maior risco (ex.: top 10% / 20%);
  - Precision-Recall AUC;
  - Comparação com baseline interpretável.

- **Indicadores de negócio (proxy)**
  - Capacidade de concentrar esforços de retenção em grupos de maior risco e impacto;
  - Redução potencial de custo de turnover, assumindo ações preventivas direcionadas.

## 6. Base de Dados
- **Fonte:** IBM HR Analytics Employee Attrition Dataset (dados públicos e simulados).
- **Descrição:** Dataset contendo informações demográficas, funcionais, de remuneração e satisfação de colaboradores.

**Observações importantes:**
- Dataset estático, sem dimensão temporal;
- Riscos associados a data leakage (vazamento de informações);
- Ausência de diferenciação explícita entre desligamento voluntário e involuntário.

Essas limitações são consideradas e discutidas ao longo do projeto.

## 7. Metodologia
- Análise exploratória orientada a hipóteses de negócio;
- Tratamento de variáveis categóricas e numéricas;
- Construção de baseline interpretável;
- Avaliação de modelos supervisionados de classificação;
- Análise de trade-offs entre métricas técnicas, impacto financeiro e uso prático;
- Estruturação de outputs voltados à decisão gerencial.

## 8. Resultados
Seção dedicada à apresentação dos principais resultados:
- Métricas de performance;
- Visualizações relevantes;
- Principais fatores associados ao turnover;
- Insights acionáveis para decisões de retenção.

## 9. Limitações e Próximos Passos
- Uso de dados simulados;
- Ausência de histórico temporal;
- Necessidade de validação em dados reais;
- Simplificações na estimativa de impacto financeiro.

Possíveis extensões incluem incorporação de dados temporais, custos explícitos de erro, segmentação por áreas críticas e testes em ambiente produtivo.

## 10. Stack Utilizada
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  
- Power BI (quando aplicável)