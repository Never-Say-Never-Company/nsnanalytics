# 2. Backlog Sprint 2

A Sprint 2 agora se concentrará na implementação das funcionalidades de Alta Prioridade, focando na **construção do ETL/DW** e nos **Dashboards Essenciais (Métricas de Alto Impacto)**, conforme as US001 a US005 do Product Backlog geral.

## Objetivo da Sprint
**Implementar o processo ETL/DW, consumir dados reais da API do Jira e entregar os Dashboards Essenciais (Total de Horas, Bugs, Issues por Status), garantindo a restrição de acesso às informações de Custo para Gerentes de Projeto.**

| ID | Como | Desejo | Prioridade | Dependência | Requisito | Critérios de Aceitação |
| :---: | :--- | :--- | :--- | :--- | :--- | :--- |
| **A** | Desenvolvedor | **Implementar o fluxo ETL completo** para buscar dados do Jira e carregar no DW | Alta | S1.B | RF1, RF2, RNF6 | - O processo consegue **extrair** dados da API do Jira (usando apenas GET).<br>- Os dados são **transformados** e **carregados** no DW (Físico).<br>- O **Modelo Físico** do DW está implementado (RNF1). |
| **B** | Gerente de Projeto | **Acessar o Dashboard com indicadores chave** para **monitorar o andamento geral dos projetos**. | Alta | A | US001, RF3 | - O dashboard exibe indicadores sobre o andamento dos projetos.<br>- Os indicadores refletem **dados reais** vindos do DW. |
| **C** | Gerente de Projeto | **Visualizar o Total de Custos por projeto** para **controlar o orçamento** (acesso restrito). | Alta | B | US002, RF6, RNF4, RNF5 | - O indicador de **Total de Custos por projeto** é exibido.<br>- Apenas o **Gerente de Projetos** consegue visualizar o custo. |
| **D** | Gerente/Líder | **Ver o Total de Horas utilizadas (geral e por projeto)** para **avaliar a alocação de esforço**. | Alta | B | US003, RF7 | - O dashboard exibe o **Total de Horas (geral e por projeto)**.<br>- O dashboard exibe a **Quantidade de Horas** por atividade e por módulo (Epic/Produto/Entregável). |
| **E** | Gerente/Líder | **Acompanhar a Quantidade de Bugs (Total) e Issues por Status** para **mensurar a qualidade e o fluxo de trabalho**. | Média | B | US004, US005, RF8, RF9 | - O dashboard exibe a **Quantidade de Bugs (Total)**.<br>- O dashboard exibe a **Quantidade de Issues** por status (aguardando, em andamento, MR, concluídas). |

## Critérios gerais para declarar a Sprint 2 concluída
1.  O processo **ETL** está funcionando e carrega dados **reais** da API do Jira para o DW.
2.  Todos os dashboards essenciais (US001-US005) estão implementados e refletem dados reais do DW.
3.  A **restrição de acesso** para informações de **custo** está implementada e testada (RF6).
4.  Testes de integração entre API, ETL e DW foram realizados com sucesso (RNF11).
