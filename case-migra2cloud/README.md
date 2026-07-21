# Migração de Plataforma Obsoleta de Planejamento para Google Cloud

> Case do portfólio de Everton Silva — Gerente de Projetos / Analista Funcional Sr. / Analista de Negócios

## Visão Geral
Substituir plataforma legada de planejamento (on-premise, obsoleta e sem suporte) por solução moderna em Google Cloud (BigQuery + Looker + Cloud Run), garantindo governança, escalabilidade e redução de TCO em 35%.

## Contexto
Sistema legado monolítico em servidor único, base Oracle 11g fora de suporte, integrações via arquivo TXT, sem DR, custo alto de sustentação.

## Ficha do Projeto
| Item | Descrição |
|------|-----------|
| Metodologia | Agile Scaled (SAFe Essential) + PMBOK para governança |
| Duração | 10 meses |
| Orçamento | R$ 4.500.000 |
| Papel exercido | Gerente de Projetos |
| Status | Concluído (case didático) |

## Sistemas / Tecnologias
- Google Cloud (BigQuery, Cloud Run, Cloud Storage, Pub/Sub)
- Looker
- Dataflow
- Cloud Composer (Airflow)
- Terraform
- GitHub Actions
- Legado Oracle 11g
- SAP

## KPIs Alcançados
- Redução TCO: 35%
- Time-to-insight: dias → minutos
- Uptime: 97% → 99,95%
- Custo por consulta: -60%
- Cobertura de testes automatizados: 80%

## Principais Riscos
- Latência de integrações híbridas
- Custos de egress mal dimensionados
- Skill gap em GCP
- Compliance de dados sensíveis

## Estrutura de Pastas
```
case-migra2cloud/
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
- `arquitetura-cloud.mmd`
- `eap.mmd`

---
**Autor:** Everton Silva • [LinkedIn](https://www.linkedin.com/) • [GitHub @everton19811](https://github.com/everton19811)
