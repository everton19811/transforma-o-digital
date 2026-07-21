**Case:** Modernização do Sistema de Estrutura Mercadológica (Low Platform)  
**Fase:** 03-execucao  
**Documento:** Arquitetura Solucao

---

## Arquitetura Alvo
Ver `diagramas/` para diagrama detalhado.

### Componentes
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

### Padrões
- API-first (OpenAPI 3.0)
- Eventos assíncronos onde couber
- Observabilidade (logs, métricas, tracing)
- Segurança em camadas (IAM, mTLS, criptografia em repouso e trânsito)
- LGPD by design
