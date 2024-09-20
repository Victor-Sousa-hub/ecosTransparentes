# Análise de Dados Parlamentares - Câmara dos Deputados

Este projeto utiliza dados do portal da transparência da Câmara dos Deputados para realizar uma análise básica da composição do legislativo brasileiro, focando na distribuição de partidos e na criação de gráficos interativos por estado.

## Visão Geral

Através de uma requisição à API pública da Câmara dos Deputados, coletamos informações sobre os deputados e as armazenamos em um formato estruturado (dicionário e dataframe). Em seguida, realizamos a contagem dos partidos representados e criamos visualizações para entender melhor a distribuição dos partidos no congresso.

Além disso, implementamos um gráfico interativo que permite filtrar os dados por estado, mostrando o número de deputados por partido para o estado selecionado.

## Requisitos

- Python 3.x
- Bibliotecas necessárias:
  - `httpx`
  - `pandas`
  - `matplotlib`
  - `ipywidgets`

## Como rodar o projeto

1. Instale as dependências necessárias utilizando o seguinte comando:

   ```bash
   pip install httpx pandas matplotlib ipywidgets

2. Execute o código para obter os dados dos deputados e gerar os gráficos.

3. Cada ceulua do notebook esta de alguma forma relacionada com outras então para melhor 
funcionamento rode sempre todos ao mesmo tempo uitlizando(crl+F9) ou o atalho do notebook.

Este `README.md` inclui uma descrição clara do projeto, os passos para instalação, a funcionalidade principal e os códigos explicados.
