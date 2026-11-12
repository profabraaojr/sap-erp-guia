# SAP ERP: Guia de Estudo por Setor

Repositório aberto para quem quer aprender SAP a partir dos processos de negócio: financeiro, logística, vendas, produção, manutenção, RH, qualidade e projetos.

A organização segue o ERP: cada pasta é um setor da empresa e reúne os módulos, as transações (T-codes), as fórmulas e as funções que ele usa no dia a dia.

## Como usar

1. Escolha o setor que você quer estudar.
2. Leia a visão geral do módulo e o fluxo do processo.
3. Use as transações indicadas para praticar em um ambiente de treinamento SAP.
4. Confira sempre o código na sua versão do sistema (transação SE93 ou tabela TSTC), porque nomes e telas mudam entre versões.

## Estrutura

| Setor | Módulos | Situação |
|---|---|---|
| [financeiro](financeiro/) | FI (Contabilidade Financeira), CO (Controladoria) | Piloto em produção |
| [logistica](logistica/) | MM (Materiais), WM (Gestão de Armazém), TM (Gestão de Transportes) | Planejado |
| [vendas](vendas/) | SD (Vendas e Distribuição) | Planejado |
| [producao](producao/) | PP (Planejamento e Produção) | Planejado |
| [manutencao](manutencao/) | PM (Gestão de Manutenção) | Planejado |
| [rh](rh/) | HCM (Gestão de Capital Humano) | Planejado |
| [qualidade](qualidade/) | QM (Gestão da Qualidade) | Planejado |
| [projetos](projetos/) | PS (Sistema de Projetos) | Planejado |

## Fontes

O conteúdo é escrito com base em documentação aberta e no próprio sistema SAP. Não reproduzimos manuais protegidos por direitos autorais. As fontes de referência são:

- SAP Help Portal (help.sap.com), documentação oficial dos módulos.
- Transação SE93 e tabela TSTC do próprio sistema, para conferir códigos de transação.

## Contribuir

Contribuições são bem-vindas. Abra uma issue ou um pull request com o módulo, a transação ou o processo que você quer incluir, e cite a fonte de onde tirou a informação.
