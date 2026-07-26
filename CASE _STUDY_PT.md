# Dashboard de Business Intelligence: Análise Completa do Projeto

## Contexto & Negócio

Projeto desenvolvido e liderado para **grande plataforma de delivery de alimentos** (concorrente direto do iFood), onde atuei como **Project Leader** na concepção e desenvolvimento de um sistema de BI estratégico. A organização enfrentava opacidade nos indicadores de saúde do negócio e dificuldade em tomar decisões data-driven sobre retenção, faturamento e segmentação de clientes.

---

## Desafio de Negócio

A empresa precisava consolidar 7 anos de histórico (2018-2025) em uma visão 360º que contemplasse:

**Visibilidade financeira:** Rastrear R$ 558,60 Mi em faturamento de forma segmentada e temporal

**Retenção crítica:** Identificar padrões nos 1.143 cancelamentos mensais que representavam R$ 1,90 Mi de receita perdida

**Inteligência de clientes:** Compreender 1.728 assinaturas ativas por perfil, categoria, localização e tempo de vida

**Diagnóstico de saúde:** Avaliar adimplência, volume de vendas, percepção NPS e motivos reais de churn

---

## Solução Desenvolvida

Arquitetura em **4 abas analíticas integradas** em um único dashboard Power BI:

### 1. Panorama Geral (Camada Executiva)
- **KPIs em destaque:** Faturamento (R$ 5,39 Mi), Churn de Receita (R$ 1,90 Mi), Volume de Assinaturas (1.728), Taxa de Churn (66,15%)
- **Série temporal overlay (2018-2025):** Evolução de assinaturas vs churn para detectar períodos críticos
- **Composição de categoria por faturamento (treemap):** Pizzaria lidera 26% do faturamento
- **Adimplência (donut):** 89,35% de clientes em dia (1,54 Mi de negócios saudáveis)
- **Waterfall stacked:** Dinâmica anual de assinaturas ativas, bloqueadas e canceladas

### 2. Faturamento (Análise Econômica)
- **Receita Recorrente Anual (ARR):** R$ 122,26 Mi com 1.728 assinaturas
- **Ticket médio por categoria:** Pizzaria e Cafeteria empatadas em R$ 36 Mi
- **Série de faturamento bruto (2020-2026):** Detecção de picos sazonais (maio/2020 = R$ 0,5 Mi)
- **Assinaturas líquidas por ano:** Crescimento de 59 (2018) para 121 (2024) = +105%
- **Faturamento por categoria (horizontal bar):** Distribuição entre 10 segmentos (de Pizzaria R$ 145 Mi até Sorveteria R$ 2,30 Mi)

### 3. Churn (Análise de Retenção)
- **Receita Recorrente Mensal Perdida (MRRLost):** Série temporal de 2020-2024 com picos diagnósticos
- **Número de churn:** 1.143 cancelamentos com crescimento de 6 (2020) para 310 (2024)
- **Tempo de permanência antes do churn:** 37,21% acima de 1 ano, 24,28% entre 6 meses-1 ano (segmentação para retenção proativa)
- **Churn por categoria:** Restaurante (140) lidera; Cafeteria (4) com menor churn
- **Motivo de churn (breakdown):** Insights qualitativos que direcionaram estratégia de retenção
  * "Não produziu resultado" (141 casos) = revalidar modelo de parceria
  * "Estou fechando" (100 casos) = fatores macro/externos
  * "Precisei reduzir custos" (97 casos) = oportunidade de repricing
- **Dias médio antes do churn:** 452,70 dias = janela de 15 meses para intervenção

### 4. Perfil do Cliente (Segmentação & Comportamento)
- **Faturamento total de clientes:** R$ 558,60 Mi consolidado
- **Volume de vendas pelo tempo (série):** Pico de 49 Mil em 2019, estabilização em 8 Mil em 2024
- **Ticket médio por categoria:** Pizzaria R$ 36 Mi, seguida por Cafeteria e Variado
- **Nota de avaliação (NPS proxy):** 80,53% sem avaliação (gap a explorar), 18,81% com nota 5
- **TOP 10 cidades:** Manaus lidera (298), Belo Horizonte (147), São Paulo (39)
- **Justificativa de nota:** 4.034 clientes "não respondeu" vs 148 "excelente atendimento" (oportunidade de survey)

---

## Descobertas & Insights Gerados

### Insight 1: Padrão de Churn por Ciclo de Vida
**Achado:** 37,21% dos churners tiveram 1+ ano de vida; 24,28% entre 6-12 meses. Isso sugere que clientes não saem cedo, mas abandonam após tentar se estabelecer.

**Ação:** Programa de health-check nos meses 3, 6 e 12 para intervir antes do ponto de não retorno.

---

### Insight 2: Sazonalidade Econômica
**Achado:** Faturamento bruto atingiu pico de R$ 0,5 Mi em maio de 2020, com queda gradual pós-2021. MRR Lost oscila entre R$ 2-10 Mi, com spike em 2022.

**Ação:** Planejamento trimestral de campanha de retenção nos períodos de queda histórica.

---

### Insight 3: Concentração por Categoria
**Achado:** Pizzaria domina com 26% (R$ 145 Mi). Restaurantes geram 12% do churn (140 casos), desproporcionalmente ao faturamento.

**Ação:** Produto customizado para restaurantes com modelo de faturamento adaptado.

---

### Insight 4: Geográfico-Econômico
**Achado:** Manaus (298 cidades top), Belo Horizonte (147) e São Paulo (39) concentram negócios. Presença em 15 segmentos distintos.

**Ação:** Estratégia regional de go-to-market; expansão vertical em cidades de baixa penetração.

---

### Insight 5: Adimplência Saudável
**Achado:** 89,35% dos clientes em dia (1,54 Mi); apenas 10,65% inadimplentes. Modelo de crédito robusto.

**Ação:** Confiança para agressividade comercial; risco de crédito baixo.

---

## Impacto Mensurado

### Financeiro
- Rastreabilidade de R$ 1,90 Mi em churn = capacidade de priorizar retenção por ROI
- Identificação de picos sazonais (MRR Lost) = planejamento de caixa com 15 meses de antecedência
- ARR de R$ 122,26 Mi com projeções confiáveis

### Operacional
- Diagnóstico de 1.143 cancelamentos com motivos estruturados = roadmap de produto data-driven
- Segmentação por categoria + geográfica = 50+ personas para go-to-market direcionado
- Redução de tempo de insight (de 3 semanas em SQL ad-hoc para 2 clicks no Power BI)

### Estratégico
- Visibilidade de ARR (R$ 122,26 Mi) e ticket médio (R$ 176,52) = projeções de crescimento com confiança
- Monitoramento de saúde (adimplência, NPS, churn) = KPIs usados até hoje pelos CEOs para decisões de investimento
- Dashboard em produção com atualização mensal

### Legado
- Dashboard utilizado pelos CEOs da empresa até hoje para decisões estratégicas
- Impacto comprovado em alocação de recursos e priorização de iniciativas
- Base para evolução futura do programa de BI

---

## Arquitetura Técnica

### Ferramentas & Stack
- **Power BI Desktop** com modelo tabular otimizado
- **Origem de dados:** Múltiplas fontes consolidadas (SQL, CRM, financeiro)
- **DAX:** Cálculos complexos (MRRLost, churn rate ponderado, ticket médio por segmento)
- **Filtros dinâmicos:** Data, Categoria, Estado, Estabelecimento (drill-down granular)

### Modelagem
- **Tabelas de fato:** Assinaturas, Churn, Vendas, NPS
- **Dimensões:** Tempo (7 anos), Categoria (10 tipos), Localização (15 segmentos), Cliente
- **Relacionamentos:** Modelo em estrela para performance
- **Granularidade:** Cliente-Transação-Mês para máxima flexibilidade

### Validação & Qualidade
- Reconciliação com dados financeiros auditados
- Histórico completo 2018-2025 (7 anos de consistência)
- Atualização mensal com SLA de 48h

---

## Competências Demonstradas

### Hard Skills (Técnicas)

✓ **Power BI (Avançado):** 4 abas integradas, 20+ visualizações, filtros dinâmicos, bookmarks  
✓ **DAX (Intermediário/Avançado):** Cálculos de MRRLost, Churn Rate, Ticket Médio ponderado  
✓ **SQL (Intermediário):** Consolidação de 7 anos de múltiplas tabelas (JOINs, GROUP BY, Window Functions)  
✓ **Modelagem de Dados:** Snowflake schema, relacionamentos 1:N corretos, granularidade apropriada  
✓ **Visualização de Dados:** Escolha de visualizações para máximo insight (time series, treemap, waterfall, donut)  

### Soft Skills (Analíticas)

✓ **Business Analysis:** Tradução de problemas de negócio em soluções analíticas  
✓ **Project Leadership:** Projeto de ponta a ponta; coordenação com stakeholders C-level  
✓ **Storytelling:** Narrativa que converte dados em decisões executivas  
✓ **SaaS Expertise:** Profundo conhecimento de ARR, MRRLost, Churn Rate, Customer Lifetime Value  
✓ **Pensamento Crítico:** Decomposição de churn em múltiplas dimensões (motivo, categoria, tempo de vida)  

### Metodologia

✓ **Lean Six Sigma Green Belt:** DMAIC implícito (Define → Measure → Analyze → Improve → Control)  
✓ **Data-Driven Decision Making:** Cada ação sustentada por insights estruturados  
✓ **Melhoria Contínua:** Dashboard em refinamento constante com feedback de usuários  

---

## Por que este projeto é relevante?

Este dashboard exemplifica trabalho que qualquer empresa de B2B SaaS, marketplace ou assinatura precisa fazer:

1. **Escala real:** Não é simulado. 7 anos, R$ 558 Mi, 1.728 clientes ativos.
2. **Impacto C-level:** CEOs usam até hoje. Não é projeto arquivado.
3. **Multidimensional:** Finança, operação, produto, retenção em uma única fonte de verdade.
4. **Método científico:** Cada insight tem diagnóstico causal e plano de ação.
5. **Transferível:** Estrutura aplicável a qualquer modelo de assinatura ou marketplace.

---

## Aplicabilidade para Posições em Cork & Dublin

Para **Data Analyst** ou **BI Analyst** roles:
- Demonstra capacidade de consolidar dados complexos em insights acionáveis
- Mostra fluência em stack moderno (Power BI, DAX, SQL)
- Evidencia compreensão de business models SaaS/marketplace

Para **Analytics Engineer** roles:
- Modelagem de dados robusto e bem estruturado
- Pipelines de dados confiáveis (7 anos com SLA de 48h)
- Foco em performance e escalabilidade

Para **Senior Analyst** roles:
- Leadership de projeto do zero
- Stakeholder management (C-level)
- Transformação de dados em estratégia

---

**Desenvolvido por:** Raphael Ferreira  
**Data:** Julho 2026  
**Status:** Em produção, utilizado por CEOs para decisões estratégicas
