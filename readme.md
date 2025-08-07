<h1 align="center"> Projeto de Análise de Evasão de Clientes </h1>

<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=%20Done&color=GREEN&style=for-the-badge"/>
</p>

---
<p align="center">
  <a href="https://www.python.org/">
    <img alt="Python" src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python">
  </a>
  <a href="https://jupyter.org/">
    <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter">
  </a>
  <a href="https://pandas.pydata.org/">
    <img alt="Pandas" src="https://img.shields.io/badge/Pandas-1.5%2B-lightgrey?logo=pandas">
  </a>
  <a href="https://seaborn.pydata.org/">
    <img alt="Seaborn" src="https://img.shields.io/badge/Seaborn-0.11%2B-lightblue?logo=python">
  </a>
  <a href="https://matplotlib.org/">
    <img alt="Matplotlib" src="https://img.shields.io/badge/Matplotlib-3.5%2B-darkgreen?logo=python">
  </a>
</p>

[![GitHub Repo stars](https://img.shields.io/github/stars/HaydenUFSC/02_challenge-data-science-?style=social)](https://github.com/HaydenUFSC/03_challenge-data-science)
[![GitHub forks](https://img.shields.io/github/forks/HaydenUFSC/02_challenge-data-science-?style=social)](https://github.com/HaydenUFSC/03_challenge-data-science/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/HaydenUFSC/02_challenge-data-science-?style=social)](https://github.com/HaydenUFSC/03_challenge-data-science/watchers)

---

## 📘 Introdução

Este projeto tem como objetivo explorar dados de clientes de uma empresa de telecomunicações e entender os fatores que levam à evasão (churn). Por meio de análise exploratória e visualizações, buscamos encontrar padrões e fornecer recomendações que possam ajudar a reduzir a taxa de cancelamento.

## 🧹 Limpeza e Tratamento de Dados

- Importação dos dados a partir de um arquivo JSON.
- Padronização e renomeação das colunas para facilitar a manipulação.
- Verificação e remoção de:
  - Valores ausentes.
  - Dados duplicados.
  - Inconsistências em variáveis categóricas (como "Churn").
  - Conversão de colunas numéricas que estavam como texto.
- Criação da coluna `Contas_Diarias`, a partir do valor mensal dividido por 30.

## 📊 Análise Exploratória

Foram realizadas análises descritivas e visualizações para melhor compreender o comportamento dos clientes:

- **Distribuição de Churn:** Gráficos de barras e pizza mostrando a proporção de clientes que cancelaram.
- **Categóricas vs. Churn:** Análises de churn por gênero, tipo de contrato, forma de pagamento e outros.
- **Numéricas vs. Churn:** Gráficos de boxplot e histogramas para tempo de permanência, gastos totais e faturamento mensal.

## 📈 Conclusões e Insights

- Clientes com **contrato mensal** estão mais propensos a evadir.
- Usuários com **baixo tempo de permanência** e **baixo gasto total** tendem a cancelar com mais frequência.
- Métodos de pagamento automáticos parecem reter mais clientes.
- A variável `Contas_Diarias` indica que muitos clientes que evadem geram pouco faturamento diário.

## ✅ Recomendações

- Incentivar contratos anuais com descontos ou bônus.
- Criar ações de retenção nas primeiras semanas do cliente.
- Oferecer benefícios para pagamentos automáticos.
- Identificar e abordar clientes com baixo engajamento rapidamente.

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT.  
Sinta-se livre para utilizar, modificar e compartilhar, mas lembre-se de dar os devidos créditos caso ele te leve ao sucesso. 😎

---

## 👨‍💻 Autor

| [<img src="https://avatars.githubusercontent.com/u/79289647?v=4" width=115><br><sub>Carlos Hayden</sub>](https://github.com/JunhaumHayden) |
| :---: |

© 2025 - Projeto de Análise de Evasão de Clientes
