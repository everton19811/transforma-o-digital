**Case:** Migração de Plataforma Obsoleta de Planejamento para Google Cloud  
**Fase:** 03-execucao  
**Documento:** Arquitetura Solucao

---

## Arquitetura Alvo
Ver `diagramas/` para diagrama detalhado.

### Componentes
- Google Cloud (BigQuery, Cloud Run, Cloud Storage, Pub/Sub)
- Looker
- Dataflow
- Cloud Composer (Airflow)
- Terraform
- GitHub Actions
- Legado Oracle 11g
- SAP

### Padrões
- API-first (OpenAPI 3.0)
- Eventos assíncronos onde couber
- Observabilidade (logs, métricas, tracing)
- Segurança em camadas (IAM, mTLS, criptografia em repouso e trânsito)
- LGPD by design
