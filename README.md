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

### Descrição Técnica  

- **Nome do teste:** `recommender_system_test`.  
- **Grupos:** A (controle) e B (teste).  
- **Período do teste:**  
  - Início: 07-12-2020.  
  - Final: 01-01-2021.  
- **Corte para novos usuários:** 21-12-2020.  
- **Público-alvo:** 15% de novos usuários da região da UE.  
- **Participantes esperados:** 6000 usuários.  

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

