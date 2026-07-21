**Case:** Modernização do Sistema de Estrutura Mercadológica (Low Platform)  
**Fase:** 01-iniciacao  
**Documento:** Project Charter

---

## 1. Identificação
- **Nome:** Modernização do Sistema de Estrutura Mercadológica (Low Platform)
- **Sponsor:** Diretoria Executiva
- **Gerente de Projetos:** Everton Silva
- **Duração:** 12 meses
- **Orçamento:** R$ 5.800.000

## 2. Justificativa
Estrutura mercadológica é o coração da precificação, sortimento e BI. Legado em AS400 com janela batch noturna, mudanças demoram 48h para refletir no PDV, alto risco operacional.

## 3. Objetivo SMART
Substituir sistema legado de estrutura mercadológica (categorias, subcategorias, segmentos) em baixa plataforma (Cobol/AS400) por microserviços em nuvem, com API-first e sincronização em tempo real com ERP, PDV e e-commerce.

## 4. Escopo
### Incluso
- Levantamento AS-IS e desenho TO-BE
- Implantação da solução alvo
- Integrações com sistemas: AS400/Cobol (legado), Java Spring Boot (novo), Apache Kafka, PostgreSQL, Redis, API Gateway Kong, SAP Retail, PDV Linx, E-commerce VTEX, Power BI
- Gestão de mudança e treinamento
- Go-live e sustentação assistida (60 dias)

### Não Incluso
- Mudanças em processos de outras áreas fora do escopo definido
- Customizações não previstas nos requisitos aprovados

## 5. Premissas
- Sponsor patrocinando a mudança
- Disponibilidade de key-users
- Ambiente de homologação disponível

## 6. Restrições
- Janela de indisponibilidade limitada a finais de semana
- Cumprimento de calendário fiscal/operacional

## 7. Critérios de Sucesso
- Latência de propagação: 48h → <5min
- Redução de incidentes de sortimento: -80%
- Cobertura API: 100% das operações
- Redução custo AS400: -70%
- Time-to-market de nova categoria: -65%

## 8. Aprovações
| Papel | Nome | Data | Assinatura |
|-------|------|------|------------|
| Sponsor | — | — | — |
| PMO | — | — | — |
| GP | Everton Silva | — | — |
