# Logística: MM, WM e TM

Este setor reúne a cadeia de suprimentos, do pedido de compra ao estoque e ao transporte. Os códigos estão em [dados/](../dados/).

## Módulos

- **MM (Materials Management)**, com dados em [mm.json](../dados/mm.json): compras, entrada de mercadoria, estoque e verificação de faturas. Cobertura boa para estudo introdutório.
- **TM (Transportation Management)**, com dados em [tm.json](../dados/tm.json): planejamento e execução de fretes. Cobertura parcial, pois os códigos usam o prefixo /SCMTMS/ e dependem da versão.
- **WM/EWM (Warehouse Management)**, com dados em [wm.json](../dados/wm.json): gestão de armazém. Pendente. O WM clássico e o EWM têm conjuntos de transações diferentes, e ainda não há lista validada.

## Fluxo: compra ao estoque (MM)

1. Requisição de compra (ME51N), que pode gerar pedido automaticamente (ME59N).
2. Pedido de compra (ME21N).
3. Entrada da mercadoria (MIGO).
4. Lançamento da fatura do fornecedor com verificação contra o pedido (MIRO).
5. Consulta do estoque (MMBE e MB52).

## Próximos passos

- Concluir o WM/EWM com transações validadas.
- Ampliar o TM com um fluxo completo, do pedido de transporte à liquidação.
- Acrescentar movimentações e seus efeitos no estoque.
