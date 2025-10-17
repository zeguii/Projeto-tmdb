# Projeto-tmdb
# Análise Estatística de Filmes - Dataset TMDB 5000 🎬

## 📝 Descrição do Projeto

Este projeto consiste em uma análise exploratória e estatística do "TMDB 5000 Movie Dataset", um popular conjunto de dados do Kaggle com informações sobre quase 5.000 filmes. O foco da análise é investigar a relação entre métricas financeiras (orçamento e receita) e indicadores de sucesso (popularidade e nota média).

O projeto aborda um ciclo completo de análise de dados, incluindo a unificação de múltiplas fontes, limpeza de dados inválidos, parsing de colunas com estruturas complexas (JSON) e, principalmente, a aplicação de estatística descritiva e análise de correlação para gerar insights.

---

## 🚀 Objetivos da Análise

* Unificar os datasets de filmes e créditos utilizando `pandas.merge` com chaves de nomes diferentes (`left_on`, `right_on`).
* Realizar a limpeza e preparação dos dados, com foco na remoção de registros com valores financeiros inválidos (orçamento/receita zerados).
* Processar e extrair informações úteis de colunas com formato JSON (como `genres` e `keywords`) utilizando a biblioteca `ast`.
* Calcular e visualizar uma matriz de correlação para quantificar a relação entre as variáveis: `budget`, `revenue`, `popularity`, e `vote_average`.
* Responder à pergunta central: **"Investir mais dinheiro em um filme (orçamento) garante uma maior receita ou uma melhor avaliação do público?"**

---

## 🛠️ Ferramentas Utilizadas

* **Linguagem:** Python
* **Bibliotecas:** Pandas, Matplotlib, Seaborn, AST
* **Técnicas:** Análise de Correlação, Limpeza de Dados, Parsing de JSON, Análise Exploratória de Dados (EDA), Visualização de Dados.
* **Ambiente:** Google Colab

---

## 📈 Principais Insights Gerados

1.  **Orçamento vs. Receita (Correlação Forte):** Foi confirmada uma **correlação positiva e forte (0.73)** entre o orçamento (`budget`) e a receita (`revenue`). Isso indica que, estatisticamente, maiores investimentos em produção tendem a estar associados a maiores retornos financeiros.

2.  **Orçamento vs. Avaliação (Correlação Nula):** O insight mais surpreendente foi a **ausência de correlação significativa (próxima de 0.09)** entre o orçamento (`budget`) e a nota média (`vote_average`). Isso sugere fortemente que o sucesso de crítica e a satisfação do público não são garantidos apenas por altos investimentos, dependendo mais de fatores como roteiro, direção e qualidade da produção.

3.  **Popularidade e Receita:** A popularidade (`popularity`) também demonstrou uma correlação positiva forte com a receita (`revenue`), reforçando que filmes que geram mais "buzz" e são mais assistidos tendem a faturar mais.

---

## 🔗 Contato
guilherme.lima85@outlook.com

**José Guilherme** - https://www.linkedin.com/in/guilherme-carvalho-34314a342
