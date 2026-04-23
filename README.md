# 🚀 Scalable Indicator Automation Framework

This project showcases a production-grade data pipeline designed to automate the consolidation of complex strategic indicators. By replacing a highly manual, month-long process with a 10-minute automated flow, the solution delivered a 90% reduction in processing time.

📋 Business Context
In a large-scale data governance environment, the team faced a critical bottleneck: consolidating over 150 indicators from fragmented sources (manual and database-driven).
- The Challenge: The manual process took up to 30 days to complete.
- The Impact: Decision-making was delayed, and data reliability was compromised.

🏗️ Technical Architecture
The pipeline was built using a hybrid stack to handle both structured database extraction and manual external inputs:
1. Data Extraction & Storage:
   - SQL: Automated extraction of core indicators from relational databases.
   - VBA & Excel: Standardized interface for registering manual indicators from external sources, ensuring data entry consistency.
   - Parquet: Intermediate storage format used to optimize read/write speeds for large volumes.
2. Processing Layer:
   - Python: The core engine responsible for the automatic calculation of 154 indicators and the unification of multiple data sources into a single source of truth.
3. Visualization & Analytics:
   - Power BI: Import of the unified database for executive reporting and real-time statistical analysis.

📈 Key Results & Deliverables
- Speed: Automatic indicators generated in 10 minutes (90% time reduction).
- Agility: Increased decision-making speed by 40%.
- Reliability: Improved data trustworthiness by 30% through standardized business rules and automated governance.
- Scalability: Implementation of a "single source of truth" architecture capable of handling growing data volumes.

## Versão em Português
🚀 Framework de Automação de Indicadores Escalável

Este projeto apresenta um pipeline de dados de nível corporativo projetado para automatizar a consolidação de indicadores estratégicos complexos. Ao substituir um processo altamente manual que durava um mês por um fluxo automatizado de 10 minutos, a solução entregou uma redução de 90% no tempo de processamento.

📋 Contexto de Negócio
Em um ambiente de governança de dados de larga escala, a equipe enfrentava um gargalo crítico: a consolidação de mais de 150 indicadores provenientes de fontes fragmentadas (manuais e bancos de dados).
- O Desafio: O processo manual levava até 30 dias para ser concluído.
- O Impacto: A tomada de decisão era atrasada e a confiabilidade dos dados era comprometida.

🏗️ Arquitetura Técnica
O pipeline foi construído utilizando uma stack híbrida para lidar tanto com a extração de bancos de dados estruturados quanto com entradas manuais externas:
1. Extração e Armazenamento de Dados:
  - SQL: Extração automatizada de indicadores core de bancos de dados relacionais.
  - VBA & Excel: Interface padronizada para registro de indicadores manuais de fontes externas, garantindo a consistência na entrada dos dados.
  - Parquet: Formato de armazenamento intermediário utilizado para otimizar as velocidades de leitura/escrita para grandes volumes.
2. Camada de Processamento:
  - Python: O motor central responsável pelo cálculo automático de 154 indicadores e pela unificação de múltiplas fontes em uma única "fonte da verdade" (single source of truth).
3. Visualização e Analytics:
  - Power BI: Importação da base unificada para relatórios executivos e análises estatísticas em tempo real.

📈 Resultados Chave e Entregáveis
- Velocidade: Indicadores automáticos gerados em 10 minutos (redução de 90% no tempo).
- Agilidade: Aumento de 40% na velocidade de tomada de decisão.
- Confiabilidade: Melhoria de 30% na confiabilidade dos dados através de regras de negócio padronizadas e governança automatizada.
- Escalabilidade: Implementação de uma arquitetura centralizada capaz de suportar volumes crescentes de dados.
