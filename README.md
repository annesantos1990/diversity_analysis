# **Análise de Diversidade no Setor de TI**

![silhouette-profile-face-group-men-women-diverse-culture-people-diversity-racial-equality_175061-345](https://github.com/user-attachments/assets/f2d04101-d232-4a93-a395-dccc1dc18b16)

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

A análise foi conduzida a partir de um conjunto de dados que inclui informações demográficas, posição ocupacional, e faixas salariais de profissionais do setor de TI. Para isso, foram utilizadas técnicas como análise descritiva, visualização de dados e inferência estatística. A pesquisa também fez uma segmentação dos profissionais por gênero, raça, e região, cruzando essas variáveis com dados salariais e de anos de experiência.

### Ferramentas 🛠️

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

### Pré-processamento de dados

A tabela `dados_tratados` foi obtida depois do tratamento de dados no Google Colab. Para ver a limpeza, tratamento dos dados brutos e a análise exploratória acesse: [`analise_diversidade__Eslaine_Santos.ipynb`](https://github.com/annesantos1990/diversity_analysis/blob/main/analise_diversidade__Eslaine_Santos.ipynb)

### Análises e Resultados
#### 1. Análise de Dados - Diversidade no Setor de TI (2022) 📝

Os resultados aqui mostrados e discutidos foram obtidos através do dashboard feito no Looker Studio - [Link do Dashboard](https://lookerstudio.google.com/reporting/7c9deb04-7e25-4807-8f1d-f3ebc16e1c6b) 

Página do Notion com a análise detalhada e as discussões - [Link do Notion](https://giddy-shamrock-550.notion.site/Resultados-e-Conclus-es-4bb3f739611d4bb8bb6f1cf91f5e43c7?pvs=4)

**Resumo dos resultados:**

**Sub-representação**: Os dados mostram que mulheres (24,78%), pessoas não brancas (34,75%) e PCDs (1,26%) continuam representando uma minoria significativa na área de dados. 

**Disparidades geográficas**: Embora 56,51% dos entrevistados estejam fora de São Paulo, é importante notar que esse grupo abrange profissionais de 25 estados, enquanto São Paulo, sozinho, concentra 44% dos trabalhadores na área. Isso evidencia a centralização das oportunidades no estado, refletindo a maior oferta de empregos e concentração de empresas na capital paulista.

**Diferença salarial**: Um gap salarial significativo entre gêneros persiste, com homens ganhando (média salarial: R$ 10.488,63)  consideravelmente mais do que mulheres (média salarial: R$ 8.632,79), em média. Minorias raciais e étnicas também enfrentam disparidades salariais.

**Desigualdade racial**: Pessoas brancas são maioria no setor, refletindo as desigualdades raciais presentes no mercado de trabalho. A análise por etnia revela que pessoas negras e indígenas estão subrepresentadas em todos os níveis hierárquicos e recebem, em média, salários menores.

#### 2. Regressão Linear - Análise de Salários e Diversidade 💼
O modelo de reegressão foi construído no nootebook do Colab na qual pode ter acesso clicando no link a seguir: [`Regressao_Linear_Eslaine.ipynb`](https://github.com/annesantos1990/diversity_analysis/blob/main/Regressao_Linear_Eslaine.ipynb)

O modelo de regressão foi desenvolvido com o objetivo de prever os salários dos profissionais no setor de TI, identificando os fatores que mais influenciam os níveis salariais. A análise proporciona insights valiosos sobre as desigualdades presentes no setor.

**Desempenho:** O modelo apresentou um desempenho moderado, conseguindo prever salários com razoável precisão, especialmente para valores abaixo de R$ 20.000. No entanto, o modelo teve dificuldades em prever salários mais altos.

**Fatores que mais influenciam os salários:**

- **Positivos:** Cargos de gestão, experiência, senioridade, nível pleno e tamanho da empresa. Profissionais com maior experiência, em cargos de liderança e em empresas maiores tendem a receber salários mais altos.
- **A análise confirma a expectativa de que a progressão de carreira e a responsabilidade estão diretamente ligadas à remuneração no setor de TI.**

**Em resumo, o modelo demonstra que a experiência, a posição hierárquica e o tamanho da empresa são os principais determinantes dos salários no setor de TI.**


### Conclusões

Os resultados da análise do modelo de regressão para prever salários no setor de TI revelam dinâmicas importantes sobre os fatores que influenciam a remuneração dos profissionais. De um lado, variáveis como ocupação de cargos de gestão, senioridade, e experiência destacam-se como determinantes positivas, confirmando que responsabilidades maiores e progressão de carreira estão fortemente associadas a melhores salários, o que é esperado em um setor em crescimento e altamente competitivo como o de TI.

Por outro lado, fatores como a região de residência e a raça do profissional demonstram a existência de desigualdades significativas. A influência negativa de morar nas regiões Sul, Nordeste e Sudeste, mesmo com o Sudeste sendo um grande polo de oportunidades, sugere que o mercado de trabalho em TI pode ter uma distribuição desigual em termos de remuneração. Além disso, a disparidade salarial relacionada a profissionais não brancos reforça a necessidade de uma maior inclusão e equidade no setor.

A insatisfação no trabalho, correlacionada a salários mais baixos, aponta para a necessidade de melhorar as condições de trabalho e remuneração para aumentar a satisfação dos profissionais. Esses achados evidenciam a complexidade da estrutura salarial no setor de TI e reforçam a urgência de abordar questões de equidade social e regional, promovendo um ambiente de trabalho mais justo e inclusivo para todos.

#### **Principais Recomendações**:

- **Aumentar a diversidade**: Implementar estratégias de recrutamento e retenção direcionadas para atrair e manter grupos sub-representados.
- **Abordar a diferença salarial**: Realizar auditorias salariais regulares e implementar práticas de remuneração equitativa.
- **Promover diversidade geográfica**: Expandir as operações para regiões fora dos principais polos de TI.
- **Fomentar culturas inclusivas**: Criar ambientes de trabalho inclusivos que valorizem a diversidade e promovam oportunidades iguais.
- **Aprimorar a coleta de dados**: Coletar dados mais granulares para entender melhor as causas das disparidades e medir o impacto das iniciativas de diversidade.


###  Links de Interesse:

* **Dashboard Looker Studio:** [Dashboard - Análise de Diversidade](https://lookerstudio.google.com/reporting/7c9deb04-7e25-4807-8f1d-f3ebc16e1c6b)
* **Página com os Resultados e Discussões detalhadas desse projeto**: [Notion](https://giddy-shamrock-550.notion.site/Resultados-e-Conclus-es-4bb3f739611d4bb8bb6f1cf91f5e43c7?pvs=4)

### Contato:

* [**LinkedIn**](https://www.linkedin.com/in/eslaine-santos/)


