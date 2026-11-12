# Vendas: SD

Este setor cobre o ciclo de vendas e distribuição, do pedido ao faturamento. Os códigos estão em [dados/sd.json](../dados/sd.json).

## Fluxo: pedido ao faturamento

1. Cadastro do cliente (XD01).
2. Cotação, se houver negociação (VA21), e pedido de venda (VA01).
3. Liberação de pedidos bloqueados por crédito, quando necessário (VKM3).
4. Remessa de saída, com separação e saída de mercadoria (VL01N).
5. Faturamento (VF01) e consulta do faturamento pendente (VF04).

## Conceitos-chave

- **Preço e condições**: as condições de preço são mantidas em V/06 e determinadas automaticamente no pedido.
- **Bloqueio de crédito**: pedidos podem ficar retidos até liberação manual.

## Próximos passos

- Acrescentar a determinação de preço com exemplos.
- Incluir devoluções e cancelamentos de fatura.
