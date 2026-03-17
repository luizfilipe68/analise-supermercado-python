# Análise de Produtos de Supermercado (Chile)

## Visão Geral do Projeto

Este projeto de Ciência de Dados tem como objetivo principal analisar a base de dados de produtos de um supermercado localizado no Chile. Através da aplicação de conceitos de **Estatística Descritiva e Inferencial**, **Visualização de Dados** e **Programação em Python**, buscamos extrair *insights* valiosos sobre o comportamento dos produtos, preços, descontos e distribuição entre diferentes categorias. O trabalho culmina na apresentação de conclusões que podem auxiliar na tomada de decisões estratégicas para o negócio.

## Problema de Negócio

O estudo foi guiado por perguntas de negócio fundamentais para os **Stakeholders** do supermercado, visando otimizar estratégias de precificação, promoções e gestão de estoque. As principais questões abordadas incluem:

*   Quais categorias de produtos possuem maior quantidade de itens disponíveis?
*   Quais categorias apresentam os maiores preços médios?
*   Como se distribui o preço dos produtos na base de dados?
*   Existem produtos com descontos muito elevados? Qual a relação entre o preço normal e o preço com desconto?
*   Quais categorias concentram os produtos mais caros ou mais baratos?

## Metodologia

A análise seguiu um fluxo de trabalho estruturado, utilizando as seguintes etapas e conceitos:

### 1. Coleta e Preparação de Dados

*   **Python: Coleta de Dados:** Carregamento da base de dados `supermercado.csv` utilizando a biblioteca `pandas`.
*   **Python: Tratamento de Dados & Preparação de Dados:** Realização de limpeza de dados, incluindo a remoção de duplicatas e tratamento inicial de valores ausentes, garantindo a qualidade dos dados para as análises subsequentes.

### 2. Análise Exploratória de Dados (AED)

*   **Estatística Descritiva:** Cálculo de métricas como **Média**, **Desvio Padrão** e **Variância** para entender a dispersão e a tendência central dos preços dos produtos.
*   **Visualização de Dados:** Utilização de **Histogramas** para visualizar a **Distribuição Normal** (ou a ausência dela) dos preços, identificando padrões e anomalias.

### 3. Análise Estatística Inferencial (Próximos Passos)

*   **Amostragem Estratificada:** (Sugestão para futuras análises) Caso a base de dados fosse maior, a aplicação de amostragem estratificada seria crucial para garantir a representatividade de diferentes categorias de produtos em análises inferenciais.
*   **Estatística Inferencial:** (Sugestão para futuras análises) Aplicação de testes de hipóteses para tirar conclusões sobre a população de produtos com base na amostra, por exemplo, comparando preços médios entre categorias.

### 4. Visualização Avançada e Storytelling

*   **Python: Visualização de Dados:** Exploração de gráficos mais avançados como **Box Plots** (para identificar *outliers* e a distribuição dos quartis), **Gráficos de Dispersão** (para analisar a relação entre preço e desconto) e **Gráficos Combinados** (para apresentar múltiplas variáveis de forma integrada).
*   **Plotly Express:** (Sugestão para futuras análises) Utilização desta biblioteca para criar visualizações interativas e dinâmicas, enriquecendo a exploração dos dados.
*   **Storytelling:** Organização dos *insights* e visualizações em uma narrativa coesa, explicando o **Equilíbrio** e **Desequilíbrio** nas vendas ou precificação, e comunicando os resultados de forma clara e persuasiva.

## Tecnologias Utilizadas

*   Python
*   Pandas
*   Matplotlib
*   Seaborn
*   Jupyter Notebook

## Como Executar o Projeto

1.  Clone o repositório:
    ```bash
    git clone https://github.com/luizfilipe68/analise-supermercado-python.git
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd analise-supermercado-python
    ```
3.  Instale as dependências (certifique-se de que o arquivo `requirements.txt` esteja correto):
    ```bash
    pip install -r requirements.txt
    ```
4.  Abra o Jupyter Notebook:
    ```bash
    jupyter notebook supermarket_data_science_template.ipynb
    ```

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir *issues* ou *pull requests*.

## Autor

Luiz Filipe F.
