## Teste A/B - **Recommender System Test**

### Sobre o Projeto  
Este projeto realiza a análise de um teste A/B conduzido para avaliar os impactos de uma recomendação de sistema aprimorada em um ecommerce. O objetivo principal é analisar as conversões em cada etapa do funil de vendas e determinar se as mudanças propostas aumentam significativamente a interação dos usuários com o site, especialmente em eventos como visualizações de produtos, adição de itens ao carrinho e compras.

---

### Objetivos do Estudo  
- Avaliar se o novo sistema de recomendação melhora a conversão do funil:  
  **`product_page → product_cart → purchase`**.  
- Verificar se há um aumento de pelo menos **10%** em cada etapa do funil dentro de até 14 dias após o cadastro.  
- Analisar a eficácia do novo sistema por meio de um teste A/B utilizando métricas estatísticas robustas.

---

### Metodologia  

#### 1. **Exploração de Dados**  
- Identificação e tratamento de tipos de dados inconsistentes.  
- Verificação de valores ausentes e duplicados.  
- Caracterização de dados importantes como o número de eventos por usuário e a distribuição de eventos ao longo do período.

#### 2. **Análise Exploratória de Dados (AED)**  
- Análise de conversão em cada etapa do funil.  
- Comparação da distribuição de eventos entre os grupos A (controle) e B (teste).  
- Avaliação de particularidades nos dados que possam impactar os resultados.

#### 3. **Teste Estatístico (Z-test)**  
- Verificação da diferença estatística entre as proporções de conversão dos grupos.  
- Avaliação da significância estatística dos resultados.

---

### Descrição Técnica do Teste  

- **Nome do teste:** `recommender_system_test`.  
- **Grupos:** A (controle) e B (teste).  
- **Período do teste:**  
  - Início: 07-12-2020.  
  - Final: 01-01-2021.  
- **Corte para novos usuários:** 21-12-2020.  
- **Público-alvo:** 15% de novos usuários da região da UE.  
- **Participantes esperados:** 6000 usuários.  

---

### Dados  

1. **`ab_project_marketing_events_us.csv`**:  
   Calendário de eventos de marketing para 2020.  

2. **`final_ab_new_users_upd_us.csv`**:  
   Dados de novos usuários registrados entre 7 e 21 de dezembro de 2020.  

3. **`final_ab_events_upd_us.csv`**:  
   Histórico de eventos dos novos usuários de 7 de dezembro de 2020 a 1 de janeiro de 2021.  

4. **`final_ab_participants_upd_us.csv`**:  
   Informações sobre os participantes do teste A/B.  

---

### Ferramentas Utilizadas  

- **Linguagem:** Python 3.x.  
- **Bibliotecas:**  
  - `Pandas`: Manipulação e análise de dados.  
  - `Matplotlib` & `Seaborn`: Visualização de dados.  
  - `SciPy`: Estatísticas e testes de hipóteses.
    
---

### Como Executar o Projeto

1. Clone o repositório;
2. Navegue até o diretório do projeto;
3. Abra o projeto no seu IDE favorito;
4. Instale as dependências;
5. Execute o script principal.
   
### Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

--------------------------

## A/B Test - **Recommender System Test**

### About the Project  
This project analyzes an A/B test conducted to evaluate the impacts of an enhanced recommendation system in an ecommerce platform. The main objective is to analyze conversions at each stage of the sales funnel and determine if the proposed changes significantly increase user interaction with the website, especially in events like product views, adding items to the cart, and making purchases.

---

### Study Objectives  
- Assess whether the new recommendation system improves conversion in the funnel:  
  **`product_page → product_cart → purchase`**.  
- Verify if there is at least a **10%** increase at each funnel stage within 14 days after registration.  
- Analyze the effectiveness of the new system using an A/B test with robust statistical metrics.

---

### Methodology  

#### 1. **Data Exploration**  
- Identification and handling of inconsistent data types.  
- Checking for missing and duplicate values.  
- Characterization of important data, such as the number of events per user and event distribution over time.

#### 2. **Exploratory Data Analysis (EDA)**  
- Conversion analysis at each stage of the funnel.  
- Comparison of event distribution between groups A (control) and B (test).  
- Evaluation of data peculiarities that could impact the results.

#### 3. **Statistical Test (Z-test)**  
- Checking for statistical differences between conversion proportions of the groups.  
- Assessing the statistical significance of the results.

---

### Technical Test Description  

- **Test Name:** `recommender_system_test`.  
- **Groups:** A (control) and B (test).  
- **Test Period:**  
  - Start: 07-12-2020.  
  - End: 01-01-2021.  
- **Cut-off for new users:** 21-12-2020.  
- **Target Audience:** 15% of new users from the EU region.  
- **Expected Participants:** 6000 users.  

---

### Data  

1. **`ab_project_marketing_events_us.csv`**:  
   Marketing event calendar for 2020.  

2. **`final_ab_new_users_upd_us.csv`**:  
   Data of new users registered between December 7 and 21, 2020.  

3. **`final_ab_events_upd_us.csv`**:  
   Event history for new users from December 7, 2020, to January 1, 2021.  

4. **`final_ab_participants_upd_us.csv`**:  
   Information about A/B test participants.  

---

### Tools Used  

- **Language:** Python 3.x.  
- **Libraries:**  
  - `Pandas`: Data manipulation and analysis.  
  - `Matplotlib` & `Seaborn`: Data visualization.  
  - `SciPy`: Statistics and hypothesis testing.
    
---

### How to Run the Project

1. Clone the repository;
2. Navigate to the project directory;
3. Open the project in your preferred IDE;
4. Install the dependencies;
5. Run the main script.
   
### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.

