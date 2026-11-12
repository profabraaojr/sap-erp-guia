# Manutenção: PM

Este setor cobre a manutenção de equipamentos e instalações. Os códigos estão em [dados/pm.json](../dados/pm.json).

## Fluxo: notificação à conclusão

1. Uma falha é registrada como notificação (IW21).
2. A notificação gera uma ordem de manutenção (IW34 ou IW31).
3. Os apontamentos registram o tempo e o trabalho realizado (IW41).
4. A ordem é concluída com confirmação geral (IW42).

## Conceitos-chave

- **Equipamento e local técnico**: objetos que recebem a manutenção (IE01, IL01).
- **Plano de manutenção preventiva**: programa as manutenções periódicas (IP10).

## Próximos passos

- Incluir o ciclo completo com exemplos.
- Acrescentar listas de tarefas e medições.
