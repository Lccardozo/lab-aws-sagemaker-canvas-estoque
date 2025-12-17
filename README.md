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

