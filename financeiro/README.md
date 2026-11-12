# Financeiro: FI e CO

Este setor cobre a contabilidade financeira (FI) e a controladoria (CO). Os códigos estão em [dados/fi-co.json](../dados/fi-co.json).

## Visão geral

- **FI (Financial Accounting)** registra os fatos contábeis: lançamentos, contas a pagar e a receber, razão e balanço.
- **CO (Controlling)** registra custos e receitas por centro de custo, ordem interna e atividade, para gestão interna.

Um lançamento em FI pode gerar reflexos em CO, por isso os dois módulos são estudados juntos.

## Fluxos principais

**Compra a pagamento (FI-AP)**

1. Cadastro do fornecedor (FK01 ou XK01).
2. Lançamento da fatura de fornecedor (FB60).
3. Consulta dos itens em aberto (FBL1N).
4. Pagamento automático (F110) ou manual, com baixa da obrigação.

**Venda a recebimento (FI-AR)**

1. Cadastro do cliente (FD01 ou XD01).
2. Lançamento do recebimento (F-28).
3. Consulta dos itens de clientes (FBL5N).

**Lançamento manual e conferência (FI-GL)**

1. Lançamento no razão (FB50).
2. Consulta do documento (FB03) e dos saldos (FS10N).

## Próximos passos

- Acrescentar ativo fixo (FI-AA) e conciliação bancária.
- Ampliar o CO com ordens internas e rateios.
- Incluir exercícios práticos com o passo a passo na tela.
