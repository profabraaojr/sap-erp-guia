# SAP ERP: Guia de Estudo por Setor

Repositório aberto para quem quer aprender SAP a partir dos processos de negócio: financeiro, logística, vendas, produção, manutenção, RH, qualidade e projetos.

A organização segue o ERP: cada pasta é um setor da empresa e traz os fluxos, os conceitos e as transações usadas no dia a dia. Os códigos estão também em formato de dados, na pasta [dados](dados/), para uso em sites, planilhas e ferramentas.

## Como usar

1. Escolha o setor que você quer estudar.
2. Leia o fluxo do processo e os conceitos-chave.
3. Use as transações indicadas para praticar em um ambiente de treinamento SAP.
4. Confira sempre o código na sua versão do sistema (transação SE93 ou tabela TSTC), porque nomes e telas mudam entre versões.

## Estrutura

| Setor | Módulos | Transações | Situação |
|---|---|---|---|
| [financeiro](financeiro/) | FI, CO | 41 | Fluxos e transações principais |
| [logistica](logistica/) | MM, TM, WM/EWM | 30, 6, 1 | MM bom; TM parcial; WM pendente |
| [vendas](vendas/) | SD | 27 | Fluxos e transações principais |
| [producao](producao/) | PP | 29 | Fluxos e transações principais |
| [manutencao](manutencao/) | PM | 30 | Fluxos e transações principais |
| [rh](rh/) | HCM | 20 | Fluxos e transações principais |
| [qualidade](qualidade/) | QM | 21 | Fluxos e transações principais |
| [projetos](projetos/) | PS | 22 | Fluxos e transações principais |

Os níveis de confiança e os limites de cada arquivo estão em [dados/README.md](dados/README.md).

## Fontes

O conteúdo foi escrito a partir de documentação aberta e de referências públicas sobre SAP. As descrições são redigidas neste repositório, e não copiadas de manuais ou de listas protegidas. As fontes de referência são:

- SAP Help Portal (help.sap.com), documentação oficial dos módulos.
- Transação SE93 e tabela TSTC do próprio sistema, para conferir códigos de transação.

Os códigos foram cruzados em várias fontes públicas. Quando as fontes divergem, o item recebe nível de confiança média e uma observação.

## Contribuir

Contribuições são bem-vindas. Abra uma issue ou um pull request com o módulo, a transação ou o processo que você quer incluir, e cite a fonte de onde tirou a informação.
