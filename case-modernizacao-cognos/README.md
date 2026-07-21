# Modernização de Infraestrutura e Aplicação Cognos TM1

> Case do portfólio de Everton Silva — Gerente de Projetos / Analista Funcional Sr. / Analista de Negócios

## Visão Geral
Modernizar a plataforma IBM Cognos TM1 (upgrade de versão + migração para servidores robustos + refatoração de cubos e regras) garantindo alta disponibilidade, performance e sustentação da operação de Planejamento.

## Contexto
Ambiente TM1 legado (v10.2) em servidores em fim de vida, cubos com regras complexas e feeders mal dimensionados, janelas de contingência frágeis e tempo de recálculo acima de SLA.

## Ficha do Projeto
| Item | Descrição |
|------|-----------|
| Metodologia | PMBOK com sprints técnicas (Kanban) |
| Duração | 6 meses |
| Orçamento | R$ 1.850.000 |
| Papel exercido | Gerente de Projetos |
| Status | Concluído (case didático) |

## Sistemas / Tecnologias
- IBM Cognos TM1 v10.2 → v11 PAW
- Planning Analytics Workspace
- Windows Server 2012 → 2022
- SQL Server
- Active Directory
- Backup Veeam

## KPIs Alcançados
- Tempo de recálculo de cubos: -60%
- Disponibilidade: 99,2% → 99,9%
- Redução de incidentes P1/P2: -70%
- Janela de backup: 6h → 1h30

## Principais Riscos
- Perda de regras/feeders na migração
- Incompatibilidade de add-ins Excel
- Indisponibilidade em ciclo orçamentário
- Falta de documentação do legado

## Estrutura de Pastas
```
case-modernizacao-cognos/
├── 01-iniciacao/
├── 02-planejamento/
├── 03-execucao/
├── 04-monitoramento-controle/
├── 05-encerramento/
├── diagramas/
└── README.md
```

Cada pasta segue os grupos de processos do PMBOK e contém documentos prontos para consulta e reuso.

## Diagramas
Ver pasta `diagramas/` (Mermaid `.mmd`):
- `gantt.mmd`
- `arquitetura.mmd`
- `eap.mmd`

---
**Autor:** Everton Silva • [LinkedIn](https://www.linkedin.com/) • [GitHub @everton19811](https://github.com/everton19811)
