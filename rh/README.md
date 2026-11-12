# Recursos Humanos: HCM

Este setor cobre a gestão de pessoas no ERP. Os códigos estão em [dados/hcm.json](../dados/hcm.json).

## Fluxos principais

**Admissão e dados do colaborador**

1. Cadastro dos dados mestres (PA30). A consulta é feita em PA20.
2. Ação de pessoal, como contratação ou promoção (PA40).

**Tempo e horário**

1. Criação do horário de trabalho (PT01).
2. Lançamento de dados de tempo (PA61 ou PA71).

**Folha de pagamento**

1. Execução do driver de folha (PC00_M99_CALC).
2. Consulta dos resultados (PC00_M99_CLSTR).

## Observação

A descrição de alguns códigos varia entre versões, como o PA41. Confirme sempre no seu sistema.

## Próximos passos

- Incluir o fluxo de folha com as etapas de simulação e liberação.
- Acrescentar a estrutura organizacional (OM).
