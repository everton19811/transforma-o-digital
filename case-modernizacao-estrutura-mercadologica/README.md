# Modernização do Sistema de Estrutura Mercadológica (Low Platform)

> Case do portfólio de Everton Silva — Gerente de Projetos / Analista Funcional Sr. / Analista de Negócios

## Visão Geral
Substituir sistema legado de estrutura mercadológica (categorias, subcategorias, segmentos) em baixa plataforma (Cobol/AS400) por microserviços em nuvem, com API-first e sincronização em tempo real com ERP, PDV e e-commerce.

## Contexto
Estrutura mercadológica é o coração da precificação, sortimento e BI. Legado em AS400 com janela batch noturna, mudanças demoram 48h para refletir no PDV, alto risco operacional.

## Ficha do Projeto
| Item | Descrição |
|------|-----------|
| Metodologia | Scrum + PMBOK (Strangler Fig Pattern) |
| Duração | 12 meses |
| Orçamento | R$ 5.800.000 |
| Papel exercido | Gerente de Projetos |
| Status | Concluído (case didático) |

## Sistemas / Tecnologias
- AS400/Cobol (legado)
- Java Spring Boot (novo)
- Apache Kafka
- PostgreSQL
- Redis
- API Gateway Kong
- SAP Retail
- PDV Linx
- E-commerce VTEX
- Power BI

## KPIs Alcançados
- Latência de propagação: 48h → <5min
- Redução de incidentes de sortimento: -80%
- Cobertura API: 100% das operações
- Redução custo AS400: -70%
- Time-to-market de nova categoria: -65%

## Principais Riscos
- Divergência entre legado e novo durante coexistência
- Impacto em PDV em produção
- Conhecimento Cobol escasso
- Integrações não documentadas

## Estrutura de Pastas
```
case-modernizacao-estrutura-mercadologica/
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
- `strangler.mmd`
- `eap.mmd`

---
**Autor:** Everton Silva • [LinkedIn](https://www.linkedin.com/) • [GitHub @everton19811](https://github.com/everton19811)
