# Análise de Churn de Clientes - Telecom X

## Visão Geral do Projeto

Este repositório contém um projeto de análise exploratória e descritiva de dados de clientes da Telecom X, focado em identificar os principais fatores que contribuem para o cancelamento de serviços (churn). O objetivo é extrair insights valiosos que possam subsidiar a equipe de Data Science na criação de modelos preditivos de churn e no desenvolvimento de estratégias de retenção eficazes.

## O que este projeto aborda?

O notebook `TelecomX_Churn.ipynb` explora os dados dos clientes da Telecom X através das seguintes etapas:

1.  **Configuração Inicial e Carregamento de Dados:** Preparação do ambiente e importação do dataset.
2.  **Limpeza e Tratamento de Dados:** Handling de valores ausentes, correção de tipos de dados e padronização.
3.  **Estatísticas Básicas e Taxa Geral de Churn:** Compreensão inicial do dataset e cálculo da taxa de churn global.
4.  **Análise Demográfica e de Perfil de Clientes:** Exploração de como fatores como gênero, idade (clientes idosos), parceiros e dependentes influenciam o churn.
5.  **Análise de Serviços e Contratos:** Investigação da relação entre os serviços contratados (internet, telefone, segurança online, etc.), tipo de contrato (mensal, anual) e métodos de pagamento com o churn.
6.  **Análise de Correlação com Churn:** Identificação das variáveis mais correlacionadas com a saída de clientes.
7.  **Visualizações e Métricas Chave:** Criação de gráficos e tabelas para ilustrar os padrões e insights.
8.  **Insights e Recomendações Finais:** Sumarização das descobertas mais relevantes e propostas de ações estratégicas para retenção de clientes.

## Estrutura do Repositório

├── TelecomX_Churn.ipynb     # Notebook Jupyter com toda a análise
├── TelecomX_Data.json       # Dataset utilizado na análise
└── README.md                # Este arquivo

## Tecnologias e Bibliotecas Utilizadas

* **Python 3.x**
* **Pandas:** Para manipulação e análise de dados.
* **NumPy:** Para operações numéricas.
* **Matplotlib:** Para visualização de dados.
* **Seaborn:** Para visualizações estatísticas mais atraentes.

## Insights e Recomendações Chave (Exemplos retirados do notebook)

* **Contratos de Curto Prazo:** Clientes com contratos mensais apresentam uma taxa de churn significativamente maior. **Recomendação:** Promover ativamente planos de 1 ou 2 anos, destacando benefícios e descontos.
* **Métodos de Pagamento:** O `Cheque Eletrônico` e o `Pagamento por Correio` estão associados a uma taxa de churn mais alta. **Recomendação:** Incentivar o uso de Débito Automático ou Cartão de Crédito com pequenos descontos ou conveniências.
* **Clientes Idosos (Senior Citizen):** Apresentam uma taxa de churn mais alta. **Recomendação:** Desenvolver programas de fidelidade ou ofertas direcionadas, considerando suas necessidades específicas.
* **Clientes sem Parceiros/Dependentes:** Tendem a ter maior churn. **Recomendação:** Criar pacotes familiares ou ofertas conjuntas para aumentar o valor percebido.
* **Encargos Mensais Elevados:** Há uma correlação positiva entre encargos mensais altos e churn. **Recomendação:** Avaliar a percepção de valor dos clientes com custos mais altos e comunicar melhor os benefícios para justificar o custo.


## 📧 Contato

Para dúvidas ou sugestões, entre em contato:

* **Wlamir Lira**
* GitHub: [wlamirlira](https://github.com/wlamirlira)
* [wlamirl@gmail.com ou www.linkedin.com/in/wlamir-lira-support-systems]
