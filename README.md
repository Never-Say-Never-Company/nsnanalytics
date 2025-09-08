# <p align = "center"> NSN Analytics - API 5º Semestre - BD 2025

Um projeto que analisa métricas de um time de desenvolvimento coleta dados sobre produtividade, qualidade e eficiência do processo. Essas informações são organizadas e processadas para gerar insights claros sobre desempenho e evolução da equipe. Por fim, os resultados são apresentados em um dashboard interativo que apoia a tomada de decisão e a melhoria contínua.

<br>


<br>
<p align="center">
  <a href="#integrantes-da-equipe">Integrantes do Time</a> |
  <a href="#descrição-do-desafio">Descrição do Desafio</a> |
  <a href="#objetivo">Objetivo do Projeto</a> |
  <a href="#requisitos">Requisitos Funcionais</a> |
  <a href="#cronograma">Cronograma</a> |
  <a href="#product-backlog">Product Backlog</a> |
  <a href="#tecnologias-utilizadas">Tecnologias Utilizadas</a>
</p>

<br>

## <a id="integrantes-da-equipe"> Integrantes do Time: </a>

| **Nome**            | **Função**        | **LinkedIn**                                                                                                                                           |
|:-------------------:|:-----------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------:|
| Cristiane Alvares   | Desenvolvedor     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/cristiane-alvares/) |
| Isaque de Souza     | Scrum Master      | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/isaque-souza-6760b8270/) |
| Paloma Soares       | Desenvolvedor     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/paloma-soares-rocha/) |
| Ricardo Campos      | Product Owner     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/ricardo-campos-ba56091b5/) |
| Vinícius Monteiro   | Desenvolvedor     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/viniciusvasm/) |

<br>

## <a id=descrição-do-desafio> Descrição do Desafio </a>

Um projeto que analisa métricas de um time de desenvolvimento coleta dados sobre produtividade, qualidade e eficiência do processo. Essas informações são organizadas e processadas para gerar insights claros sobre desempenho e evolução da equipe. Por fim, os resultados são apresentados em um dashboard interativo que apoia a tomada de decisão e a melhoria contínua.

<br>

## <a id="objetivo"> Objetivo do Projeto

O objetivo deste produto é fornecer uma plataforma de gestão e análise de desempenho de projetos que atenda tanto gestores quanto desenvolvedores. Para os gestores, o sistema oferece visão detalhada do desempenho individual e coletivo do time, permitindo gerar dashboards interativos, boards consolidados e acompanhar indicadores-chave de progresso. Para os desenvolvedores, a plataforma possibilita monitorar seu próprio desempenho, atividades concluídas e métricas pessoais, promovendo maior autoconhecimento e engajamento. O sistema garante ainda controle de acesso por perfis, assegurando que cada usuário visualize informações adequadas ao seu nível de permissão.

<br>

## <a id="requisitos"> Requisitos Funcionais </a>

| Identificador | Requisito Funcional |
|---------------|-------------------|
| I             | O sistema deve consumir dados diretamente via API do sistema de gestão de projetos. |
| II            | O sistema deve consolidar os dados em um Data Warehouse para análise. |
| III           | O sistema deve permitir a geração de indicadores de andamento dos projetos. |
| IV            | O sistema deve disponibilizar dashboards interativos para visualização de métricas. |
| V             | O sistema deve gerar boards com informações consolidadas sobre as atividades. |
| VI            | O sistema deve possibilitar o acesso com diferentes perfis de usuários, cada um com níveis de permissão distintos. |

<br>

## <a id="cronograma"> Cronograma</a>

| Sprint | Nome                        | Data Início | Data Fim | Status |
|--------|-----------------------------|------------|----------|--------|
| --     | Kick-off geral              | 25/08      | 29/08    | Ok     |
| 1      | Sprint 1                   | 08/09      | 28/09    |        |
| 2      | Sprint Review / Planning    | 29/09      | 03/10    |        |
| 3      | Sprint 2                   | 06/10      | 26/10    |        |
| 4      | Sprint Review / Planning    | 27/10      | 31/10    |        |
| 5      | Sprint 3                   | 03/11      | 23/11    |        |
| 6      | Sprint Review              | 24/11      | 28/11    |        |
| 7      | Feira de Soluções           | 04/12      | 04/12    |        |

<br>

## <a id="product-backlog"> Product BackLog</a>
| ID  | Como         | Desejo                                                                                   | Sprint | Prioridade | Dependência | Requisito |
|-----|-------------|------------------------------------------------------------------------------------------|--------|------------|------------|-----------|
| A   | Gestor       | Ver o desempenho individual de cada membro do time                                       | 1      | Alta       | II, III    | III       |
| B   | Gestor       | Visualizar o desempenho consolidado do time em projetos                                  | 1      | Alta       | II, III    | III       |
| C   | Gestor       | Gerar boards com atividades consolidadas do time                                         | 1      | Média      | I, II      | V         |
| D   | Gestor       | Definir níveis de permissão e acesso aos dashboards                                      | 1      | Alta       | VI         | VI        |
| E   | Desenvolvedor | Ter acesso restrito de acordo com meu perfil                                             | 2      | Alta       | VI         | VI        |
| F   | Desenvolvedor | Ver meu desempenho individual em cada projeto                                           | 2      | Alta       | I, II      | III       |
| G   | Desenvolvedor | Visualizar minhas atividades concluídas e pendentes                                      | 2      | Média      | I, II      | V         |
| H   | Desenvolvedor | Acessar dashboards com métricas do meu trabalho                                          | 3      | Alta       | II, III    | IV        |
| I   | Desenvolvedor | Comparar meu desempenho ao longo do tempo                                               | 3      | Média      | II, III    | III       |
| J   | Gestor       | Filtrar dashboards por projeto, membro ou período                                        | 3      | Média      | IV         | IV        |
| K   | Gestor       | Receber alertas ou notificações sobre atrasos ou bloqueios do time                       | 3      | Média      | III, IV    | III       |

<br>

## <a id="tecnologias-utilizadas"> Tecnologias Utilizadas 🛠️</a>

### **Back-end**
- **[Python:](https://www.python.org/)** Versão 3.13.7
- **[DJango:](https://www.djangoproject.com/)** Versão 5.2.6
- **[PostgreSQL:](https://www.postgresql.org/)** Versão 15.2

### **Front-end**
- **[Vue.js:](https://vuejs.org/)** Versão 3.5.13
- **[Vue Router:](https://router.vuejs.org/)** Versão 4.5.0
- **[Vuetify:](https://vuetifyjs.com/en/)** Versão 3.9.7
- **[Axios:](https://axios-http.com/)** Versão 1.8.4
- **[Chart.js:](https://www.chartjs.org/)** Versão 4.0

### **Ambiente de Execução**
- **[Node.js:](https://nodejs.org/pt)** Versão 22.14

### **Ferramentas de Desenvolvimento** 
- **[Vite:](https://vitejs.dev/)** Versão 6.2.1
- **[TypeScript:](https://www.typescriptlang.org/)** Versão 5.8.0
- **[Git:](https://git-scm.com/)** Controle de versão
- **[GitHub:](https://github.com/)** Repositório remoto
