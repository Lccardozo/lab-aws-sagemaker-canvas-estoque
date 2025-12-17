# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets, quanto mais você se engajar, mais relevante esse projeto será em seu portfólio.
-   Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
-   Faça o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importe o dataset que você selecionou.
-   Configure as variáveis de entrada e saída de acordo com os dados.
-   Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.

### 3. Analisar

-   Após o treinamento, examine as métricas de performance do modelo.
-   Verifique as principais características que influenciam as previsões.
-   Faça ajustes no modelo se necessário e re-treine até obter um desempenho satisfatório.

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.

## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.


# Predição de Custos Operacionais por Setor usando Machine Learning

## Visão Geral do Projeto

Este projeto foi desenvolvido com o objetivo de **consolidar e demonstrar conhecimentos práticos em análise de dados, engenharia de atributos e Machine Learning**, aplicados a um cenário realista de **predição de custos operacionais por setor**.

Todo o fluxo foi construído a partir de um **dataset sintético autoral**, criado programaticamente em Python, simulando operações empresariais envolvendo fatores humanos, tecnológicos e energéticos. O foco principal não foi apenas obter uma boa métrica final, mas **compreender profundamente o impacto das variáveis no custo operacional** e evoluir tecnicamente ao longo do processo.

---

## Construção do Dataset

O dataset foi gerado via script Python, resultando em um arquivo CSV com **500 registros e 18 variáveis**, representando ciclos operacionais diários de diferentes setores da empresa.

### Principais características do dataset:

* Setores distintos: TI, Operações, Manutenção, Logística e Atendimento
* Variáveis humanas (quantidade de colaboradores, horas trabalhadas, nível médio de experiência)
* Variáveis técnicas (sistemas ativos, falhas, tempo médio de resposta)
* Variáveis operacionais e financeiras (consumo energético, custo operacional, produtividade)
* Indicadores estratégicos (SLA, risco operacional e resultado final)

A geração sintética permitiu:

* Controle estatístico dos dados
* Reprodutibilidade do experimento
* Coerência lógica entre variáveis
* Criação de correlações próximas a cenários reais de negócio

Esse processo reforçou conceitos fundamentais de **engenharia de dados**, além de garantir total domínio sobre a origem e a qualidade das informações utilizadas no modelo.

---

## Preparação dos Dados

Antes do treinamento dos modelos, foram realizadas etapas clássicas de **pré-processamento**, incluindo:

* Análise exploratória dos dados (EDA)
* Verificação de tipos de dados e valores inconsistentes
* Codificação de variáveis categóricas (ex.: setor)
* Separação entre variáveis explicativas (features) e variável alvo
* Divisão dos dados em conjuntos de treino e teste

Durante essa etapa, ficou evidente a importância da **qualidade das features** para o desempenho do modelo, indo além da simples aplicação de algoritmos prontos.

---

## Engenharia de Atributos

Para melhorar a capacidade preditiva, foram criadas novas variáveis derivadas, como:

* Custo por colaborador
* Consumo energético por hora trabalhada
* Relação entre falhas de sistema e quantidade de sistemas ativos
* Indicadores normalizados de produtividade

Essa etapa foi essencial para reduzir o erro do modelo e aprofundar o entendimento sobre **quais fatores mais impactam os custos operacionais em cada setor**.

---

## Treinamento do Modelo de Machine Learning

O foco principal do treinamento foi a **predição da variável `custo_operacional_rs`**, utilizando modelos de regressão supervisionada.

O fluxo de treinamento incluiu:

* Definição de um modelo baseline
* Avaliação inicial por métricas de erro (MAE / RMSE)
* Análise do erro absoluto em relação à escala do custo
* Interpretação do erro em termos percentuais

O modelo inicial apresentou um erro médio em torno de **30–35% do valor médio do custo**, o que, apesar de elevado para uso real em produção, foi considerado **adequado como ponto de partida para aprendizado e evolução técnica**.

Esse resultado reforçou conceitos importantes como:

* Limitações de modelos simples
* Importância de relações não lineares
* Necessidade de feature engineering

---

## Avaliação e Aprendizados

Mais importante do que a métrica final, este projeto proporcionou aprendizados práticos em:

* Interpretação correta de métricas de regressão
* Comparação entre erro absoluto e erro relativo
* Entendimento do impacto das variáveis no custo
* Pensamento crítico sobre melhorias possíveis no modelo

A análise por setor permitiu observar como **diferentes áreas apresentam padrões distintos de custo**, reforçando a utilidade de modelos preditivos como ferramenta de apoio à decisão.

---

## Tecnologias Utilizadas

* Python 3.11
* Pandas e NumPy
* Scikit-learn
* Jupyter Notebook / VS Code
* Amazon SageMaker (treinamento e experimentação)

---

## Conclusão

Este projeto serviu como um **laboratório prático de Machine Learning aplicado a problemas de negócio**, integrando geração de dados, análise, modelagem e interpretação de resultados.

O processo contribuiu significativamente para o desenvolvimento do meu conhecimento em:

* Machine Learning supervisionado
* Engenharia de atributos
* Análise crítica de métricas
* Aplicação de modelos preditivos para estimativa de custos

Além disso, o projeto demonstra a capacidade de **estruturar um pipeline completo de dados**, desde a criação do dataset até a avaliação do modelo, reforçando competências essenciais para atuação em áreas como **Análise de Dados, Sistemas e Machine Learning**.

---

> Projeto desenvolvido com foco em aprendizado contínuo, clareza técnica e aplicação prática de Machine Learning em cenários realistas de negócio.

