# Challenge Telecom X: Análise de Evasão de Clientes
# 📊 Telecom X – ETL e Análise de Churn  

Este projeto foi desenvolvido como parte do desafio do programa **Oracle Next Education + Alura**, com foco no processo de **ETL (Extract, Transform, Load)** e análise da evasão de clientes (churn) da empresa fictícia **Telecom X**.  

---

## 🚀 Objetivo do Projeto  
O principal propósito foi investigar os fatores que levam clientes a cancelarem seus contratos, aplicando técnicas de limpeza e transformação de dados, além de análises exploratórias que permitiram identificar padrões relevantes.  

---

## 🛠️ Processo ETL  

- **Extração:** Os dados foram obtidos a partir da API disponibilizada no desafio e convertidos em DataFrame.  
- **Transformação:**  
  - Ajuste de tipos de variáveis (`TotalCharges`, `tenure`, etc.).  
  - Padronização dos nomes das colunas.  
  - Criação de novas variáveis derivadas, como `Contas_Diarias`, que representa o gasto médio diário de cada cliente.  
- **Carga:** O dataset final foi salvo em `.csv`, pronto para visualizações e análises posteriores.  

---

## 📊 Principais Resultados da Análise  

- **Taxa de cancelamento:** aproximadamente **26,5%** dos clientes abandonaram os serviços.  
- **Variáveis categóricas:**  
  - Contratos **mensais** apresentaram maior propensão ao churn.  
  - O método de pagamento **Cheque Eletrônico** foi o mais associado a cancelamentos.  
- **Variáveis numéricas:**  
  - Clientes com menor tempo de permanência (tenure baixo) cancelaram mais.  
  - Custos mensais elevados (`MonthlyCharges`) aumentaram o risco de evasão.  

---

## 💡 Insights e Recomendações  

- **Onboarding estratégico:** oferecer benefícios e suporte adicional nos primeiros meses.  
- **Fidelização:** incentivar contratos de longo prazo (1–2 anos).  
- **Modernização de pagamentos:** promover opções digitais e automáticas em vez de cheques.  
- **Planos acessíveis:** criar pacotes mais flexíveis para reduzir evasão relacionada a custos altos.  


