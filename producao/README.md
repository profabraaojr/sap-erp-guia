# Produção: PP

Este setor cobre o planejamento e a execução da produção. Os códigos estão em [dados/pp.json](../dados/pp.json).

## Fluxo: necessidade à ordem de produção

1. Necessidades de venda ou previsão são lançadas (MD61).
2. O MRP calcula o que comprar e o que produzir (MD01, MD02 ou MD03).
3. A necessidade aparece na situação de estoque e necessidades (MD04).
4. Ordens planejadas são convertidas em ordens de produção (CO40 ou CO41).
5. Os apontamentos registram o que foi produzido (CO11N ou CO15).

## Conceitos-chave

- **Lista de materiais (BOM)**: estrutura dos componentes de um produto (CS01 a CS03).
- **Roteiro (routing)**: sequência de operações e centros de trabalho (CA01).
- **MRP**: cálculo de necessidades de material e de planejamento de produção.

## Próximos passos

- Incluir um exemplo completo, do MRP à confirmação.
- Acrescentar a produção repetitiva.
