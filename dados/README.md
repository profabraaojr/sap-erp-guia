# Dados de transações SAP

Esta pasta reúne as transações (T-codes) de cada módulo em formato JSON, para uso por pessoas, sites, planilhas ou ferramentas como um MCP.

## Arquivos

| Arquivo | Módulo | Transações | Situação |
|---|---|---|---|
| fi-co.json | FI/CO | 41 | Completo para estudo introdutório |
| mm.json | MM | 30 | Completo para estudo introdutório |
| tm.json | TM | 6 | Parcial |
| wm.json | WM/EWM | 1 | Pendente |
| sd.json | SD | 27 | Completo para estudo introdutório |
| pp.json | PP | 29 | Completo para estudo introdutório |
| pm.json | PM | 30 | Completo para estudo introdutório |
| hcm.json | HCM (HR) | 20 | Completo para estudo introdutório |
| qm.json | QM | 21 | Completo para estudo introdutório |
| ps.json | PS | 22 | Completo para estudo introdutório |

## Estrutura de cada arquivo

```json
{
  "modulo": "FI/CO",
  "setor": "financeiro",
  "nome": "...",
  "atualizado_em": "AAAA-MM-DD",
  "aviso": "...",
  "transacoes": [
    {
      "codigo": "FB50",
      "descricao": "Lançamento manual no razão em tela única",
      "area": "FI-GL",
      "confianca": "alta",
      "observacao": "opcional"
    }
  ]
}
```

- **codigo**: o código da transação, como digitado no campo de comando do SAP.
- **descricao**: explicação escrita para este repositório, não cópia de manual.
- **area**: componente do SAP (por exemplo, FI-GL é razão contábil, FI-AP é contas a pagar).
- **confianca**: quanto a informação foi confirmada nas fontes consultadas.
- **observacao**: variações ou alertas sobre o código.

## Níveis de confiança

- **alta**: o código aparece em três ou mais fontes independentes, com a mesma função.
- **media**: aparece em uma ou duas fontes, ou a descrição varia entre fontes.
- **baixa**: encontrado em uma única fonte pouco confiável, ou depende de contexto (por exemplo, um programa que se executa pelo SE38).

## Limites

- Os códigos e as telas mudam entre versões do SAP (ECC e S/4HANA) e são customizados em cada empresa. Confirme no seu sistema pela transação SE93 ou pela tabela TSTC antes de usar em produção.
- Alguns códigos listados são programas ou menus, não transações diretas. A observação indica quando isso acontece.
- Este conjunto ainda não cobre todas as transações de cada módulo. Contribuições são bem-vindas.
