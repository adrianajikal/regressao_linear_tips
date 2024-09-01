# Projeto de Análise de Gorjetas (`tips`)

## Descrição

Este projeto realiza uma análise exploratória e modelos de regressão usando uma base de dados de gorjetas (`tips`). O objetivo é entender a relação entre o valor da gorjeta (`tip`), a conta líquida (`net_bill`) e a porcentagem da gorjeta (`tip_pct`). O projeto aborda diferentes métodos de ajuste de modelos lineares para prever a gorjeta com base na conta líquida.

## Estrutura do Projeto

- **Parte 1: Análise Exploratória**
  - Carregamento e pré-processamento dos dados.
  - Criação de novas variáveis:
    - `tip_pct`: Percentual da gorjeta em relação à conta líquida (`net_bill`).
    - `net_bill`: Conta líquida, calculada como o valor total da conta menos a gorjeta.

- **Parte 2: Ajuste de Modelos de Regressão**
  - Regressão linear simples: `tip ~ net_bill`.
  - Regressão linear usando transformação: `tip_pct ~ net_bill`.
  - Comparação dos resultados dos modelos, incluindo R².

- **Parte 3: Visualização**
  - Gráficos de dispersão com linhas de regressão para `tip ~ net_bill` e `tip_pct ~ net_bill`.
  - Comparação visual das relações entre as variáveis.


Este projeto é licenciado sob os termos da licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

Este README serve como uma boa introdução ao seu projeto e guia os usuários sobre como executar e entender o código.
