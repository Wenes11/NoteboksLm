# NotebookLM: Finanças e Data Analytics no Futebol Brasileiro

> Um estudo aprofundado sobre como a capacidade financeira e o uso de métricas avançadas (xG, VAEP, SciSkill) definiram o sucesso na Série A do Campeonato Brasileiro de 2022.

## 📖 Sobre o Projeto
Este repositório contém a curadoria de conhecimentos gerados via **Google NotebookLM** baseada em 10 fontes de estudo. O objetivo é explorar a interseção entre gestão financeira e análise de desempenho esportivo.

O notebook sintetiza como o futebol brasileiro está transicionando de avaliações subjetivas para um modelo de **gestão profissional baseada em evidências**, onde o dinheiro (receita/salários) define o patamar competitivo e os dados (analytics) otimizam a performance.

## 🧠 Principais Insights

### 1. Dinheiro Compra Sucesso? (Correlação Financeira)
As fontes indicam uma correlação direta e substancial entre poderio econômico e resultados em campeonatos de pontos corridos (longa duração).
* **Receita Bruta e Salários:** Em 2022, 4 dos 5 clubes com maior receita terminaram no Top 5. Inversamente, os times com menores folhas salariais ocuparam as últimas posições.
* **O "Combustível":** A análise compara a receita ao combustível de um carro de corrida: ter dinheiro não garante a vitória (precisa de boa gestão), mas a falta dele torna a vitória virtualmente impossível.
* **Liquidez vs. Folha:** Indicadores de endividamento ou liquidez imediata influenciam menos o resultado de campo do que a capacidade bruta de pagar altos salários e atrair talentos.

### 2. A Revolução das Métricas (Analytics)
O estudo detalha a evolução das estatísticas, saindo da contagem simples para modelos preditivos:
* **Bottom-Up (Ações):** Uso de **xG (Gols Esperados)**, **xThreat** (Ameaça Esperada) e **VAEP** para medir a qualidade de cada toque na bola.
* **Top-Down (Geral):** Algoritmos como **SciSkill** e **Elo** para classificar a força global de uma equipe ou atleta.
* **Clusterização (K-means):** Uso de Machine Learning para agrupar times por estilo de jogo baseado em 72 atributos numéricos, auxiliando na contratação de técnicos compatíveis.

### 3. Análise de Mercado e Valor (Valuation)
Como o mercado precifica os atletas hoje:
* **Modelos Preditivos:** Uso de *Random Forest* para prever o desenvolvimento futuro do valor de um atleta (prospectivo) em vez de apenas olhar para o passado.
* **Eficiência de Mercado:** O mercado de salários é considerado "otimizado" — jogadores que entregam mais resultado tendem a custar mais, reduzindo as chances de encontrar "barganhas" óbvias sem o uso de dados avançados.

## 🛠️ Ferramentas Recomendadas
O notebook listou as 5 principais plataformas para coleta de dados estatísticos (sugeridas pelo *Footure* e outras fontes):

| Plataforma | Melhor Uso |
| :--- | :--- |
| **SofaScore** | Estatísticas em tempo real e mapas de calor. |
| **FBRef** | Dados completos de ligas europeias e comparação de atletas. |
| **WhoScored** | Gráficos de zonas de toque e passes. |
| **InfoGol** | Especializado em dados de xG (Expected Goals). |
| **Footstats** | Dados específicos de campeonatos estaduais brasileiros. |

## ❓ Perguntas Respondidas (FAQ)
*O conteúdo cobre respostas para as seguintes questões:*

* **Como o desempenho financeiro influencia os resultados?**
    * *R:* A folha salarial é o maior preditor de sucesso. Times que investem mais em RH (atletas) tendem a ficar no topo da tabela.
* **O que é xG e como ele é calculado?**
    * *R:* É a probabilidade de um chute virar gol, calculada com base na distância, ângulo e contexto da jogada, reduzindo o viés de chutes de longa distância.
* **Qual a diferença entre análise subjetiva e objetiva?**
    * *R:* A análise moderna usa dados para quantificar o "intangível", como a probabilidade de uma assistência (xThreat) ou a contribuição defensiva, complementando o olho humano.

## 👤 Autor
Curadoria e análise de dados geradas por **João Vitor Vargas Martins**.
*Processado via Google NotebookLM.*
