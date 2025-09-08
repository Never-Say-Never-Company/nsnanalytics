# Backlog Sprint 1

## Objetivo da Sprint
Entregar funcionalidades iniciais para gestores visualizarem o desempenho do time e controlarem o acesso aos dashboards, garantindo que os usuários tenham permissões adequadas.

| ID  | Como   | Desejo                                                       | Prioridade | Dependência | Requisito | Critérios de Aceitação |
|-----|-------|--------------------------------------------------------------|------------|------------|-----------|----------------------|
| A   | Gestor | Ver o desempenho individual de cada membro do time          | Alta       | II, III    | III       | - Conseguir selecionar um membro do time e visualizar suas métricas de desempenho.<br>- Indicadores de progresso estão corretos e atualizados.<br>- Dados consolidados vêm do Data Warehouse. |
| B   | Gestor | Visualizar o desempenho consolidado do time em projetos     | Alta       | II, III    | III       | - Mostrar visão agregada do time por projeto.<br>- Possibilidade de filtrar por projeto ou período.<br>- Indicadores refletem dados reais do Data Warehouse. |
| C   | Gestor | Gerar boards com atividades consolidadas do time            | Média      | I, II      | V         | - Board apresenta atividades de todos os membros do time.<br>- Atividades são agrupadas por status (concluídas, pendentes, em andamento). |
| D   | Gestor | Definir níveis de permissão e acesso aos dashboards         | Alta       | VI         | VI        | - É possível criar perfis com diferentes níveis de acesso.<br>- Usuários só veem informações permitidas pelo seu perfil.<br>- Alterações de permissão são aplicadas imediatamente. |

## Critérios gerais para declarar a Sprint 1 concluída
1. Todas as histórias de usuário da sprint estão implementadas e testadas.  
2. Dados do Data Warehouse estão corretamente integrados e refletidos nos dashboards e boards.  
3. Perfis de acesso estão funcionando, com usuários vendo apenas o que têm permissão.  
4. Testes de funcionalidade foram realizados, sem bugs críticos.  
5. Feedback inicial de um gestor sobre visualização do time foi coletado e validado.  
6. Documentação mínima do sistema (como configurar perfis e visualizar dashboards) está pronta.  
