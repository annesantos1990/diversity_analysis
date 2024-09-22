# **Análise de Diversidade no Setor de TI**

---


### Introdução

Este projeto consiste em uma análise exploratória da diversidade na área de Tecnologia no Brasil. O objetivo é avaliar não apenas a representatividade de grupos minoritários no setor, mas também examinar disparidades salariais entre essas populações. Ao aprofundar nossa compreensão da composição demográfica e dos salários no setor de TI, buscamos identificar possíveis lacunas e oportunidades para promover maior equidade e inclusão.

### Objetivos

Realizar uma análise detalhada de gênero, raça e região para avaliar a presença de diversidade no setor de TI no Brasil. O objetivo é identificar possíveis desigualdades e variações na representatividade desses grupos, fornecendo percepções sobre a inclusão no setor.

### Principais perguntas

- Qual a porcentagem de pessoas pertencentes a grupos considerados minoritários no setor de TI?
- Existem disparidades salariais entre esses grupos e outros profissionais da área?
- Quais são as principais barreiras de entrada para esses grupos no setor de TI?
- Quais iniciativas ou políticas podem ser implementadas para aumentar a diversidade e reduzir a desigualdade?

### Metodologia

A análise será conduzida a partir de um conjunto de dados que inclui informações demográficas, posição ocupacional, e faixas salariais de profissionais do setor de TI. Para isso, serão utilizadas técnicas como análise descritiva, visualização de dados e inferência estatística. A pesquisa também fará uma segmentação dos profissionais por gênero, raça, e região, cruzando essas variáveis com dados salariais e de anos de experiência.

### Ferramentas

A análise será realizada utilizando ferramentas como Python (para processamento de dados e análise estatística), Power BI (para visualizações interativas), e SQL (para consultas e manipulação de grandes volumes de dados).

### Dados
Para visualizar a tabela com os dados tratados acesse: [dados_tratrados.csv](https://docs.google.com/spreadsheets/d/1bmgYRqtKdP8aKNZDjrfoB7R0PGuxRAnb-sWkTPslzPg/edit?usp=sharing)

<details> <summary> <h5>**Biblioteca dos dados:**  - Clique em ▶ para ver os detalhes </h5> </summary> 


| **Variável** | **Descrição** |
| --- | --- |
| **ID** | Um identificador exclusivo para cada registro. |
| **IDADE, FAIXA IDADE** | Idade e faixa etária dos participantes. |
| **GÊNERO, COR/RACA/ETNIA** | Informações demográficas de gênero e etnia. |
| **PCD** | Informação sobre se o participante é pessoa com deficiência. |
| **EXPERIÊNCIA_PROFISSIONAL_PREJUDICADA** | Opinião sobre se a experiência profissional foi prejudicada. |
| **ASPECTOS_PREJUDICADOS** | Áreas prejudicadas na experiência profissional. |
| **VIVE_NO_BRASIL** | Indica se a pessoa vive no Brasil. |
| **CRITÉRIOS DE DECISÃO PARA TRABALHAR** | Critérios considerados ao escolher um emprego. |
| **MODELO DE TRABALHO** | Modelo de trabalho atual (híbrido, remoto, presencial). |
| **LAYOFF EM 2022** | Informação sobre se a empresa passou por demissões em massa. |
| **ATUAÇÃO** | Área de atuação. |
| **LINGUAGENS DE TRABALHO** | Linguagens utilizadas no trabalho (por exemplo, SQL). |
| **ABERTO_OPORTUNIDADES** | Indicação de estar buscando novas oportunidades. |
| **ETNIA** | Etnia dos participantes em categorias "Branca" e "Não Branca". |

</details> 

### Pré-processamento de dados e Análises
A tabela `dados_tratados` foi obtida depois do tratamento de dados no Google Colab. Para ver a limpeza, tratamento dos dados brutos e a análise exploratória acesse:[`analise_diversidade__Eslaine_Santos.ipynb`](https://github.com/annesantos1990/diversity_analysis/blob/main/analise_diversidade__Eslaine_Santos.ipynb)

#### 1. Análise de Dados - Diversidade no Setor de TI (2022) 📝

**Arquivo**: `analise_dados.ipynb`

Este notebook contém uma análise detalhada sobre a diversidade do público na área de TI com base em dados de 2022. Algumas das perguntas respondidas incluem:

- Qual é a distribuição de gênero no setor?
- Como as diferentes etnias estão representadas?
- Existe alguma mudança nas tendências de contratação?

#### 2. Regressão Linear - Análise de Salários e Diversidade 💼

**Arquivo**: `regressao_linear.ipynb`

Neste notebook, foi realizado um modelo de **Regressão Linear,** cujo objetivo é ****predizer o salário das pessoas no setor de TI, trazendo insights de quais fatores influenciam mais ou menos nno salário dos profissionais da área.

Essa análise proporciona uma visão  aprofundada sobre os principais fatores que podem estar influenciando o cenário salarial no setor de tecnologia.


### Dashboard

As principais análises foram obtidas no Looker Studio. Para acessar clique no link abaixo: [Dashboard - Análise de Diversidade]()

### Principais Resultados:


### Links de Interesse:

Para a discussão dos resultados, explicação do dashboard, conclusões e principais insights, acesse a página a seguir:

[Resultados e Conclusões](https://www.notion.so/Resultados-e-Conclus-es-4bb3f739611d4bb8bb6f1cf91f5e43c7?pvs=21)
