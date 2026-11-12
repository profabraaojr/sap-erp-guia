# Financeiro: FI e CO

Este setor cobre a contabilidade financeira (FI) e a controladoria (CO). É o piloto do repositório.

## Visão geral

- **FI (Financial Accounting)** registra os fatos contábeis: lançamentos, contas a pagar e a receber, razão e balanço.
- **CO (Controlling)** registra os custos e receitas por centro de custo, ordem e atividade, para gestão interna.

Um lançamento feito em FI pode gerar reflexos em CO, por isso os dois módulos são estudados juntos.

## Transações de referência

As transações abaixo são as mais usadas em estudo introdutório. Confira o código e o texto na sua versão do sistema antes de usar.

| Transação | Função | Área |
|---|---|---|
| FB50 | Lançamento contábil no razão (documento genérico) | FI-GL |
| FB01 | Lançamento de documento contábil | FI-GL |
| FB03 | Exibir documento contábil | FI-GL |
| FS00 | Manutenção de contas do razão | FI-GL |
| FK01 | Criar fornecedor | FI-AP |
| FBL1N | Razão de fornecedores (contas a pagar) | FI-AP |
| FD01 | Criar cliente | FI-AR |
| FBL5N | Razão de clientes (contas a receber) | FI-AR |
| F110 | Execução do pagamento automático | FI-AP |
| KS01 | Criar centro de custo | CO-OM |
| FBL3N | Razão de contas do razão | FI-GL |

## Fluxo básico: compra a pagamento

1. Entrada de fatura de fornecedor, com reflexo em contas a pagar.
2. Pagamento automático ou manual, com baixa da obrigação.
3. Conciliação no extrato bancário.

## Próximos passos

- Ampliar o módulo FI com ativo fixo (FI-AA) e conciliação bancária.
- Incluir o módulo CO com ordens internas e rateios.
- Acrescentar exercícios práticos com o passo a passo na tela.
