**Case:** Planejamento Orçamentário Corporativo  
**Fase:** 03-execucao  
**Documento:** Arquitetura Solucao

---

## Arquitetura Alvo
Ver `diagramas/` para diagrama detalhado.

### Componentes
- SAP FI/CO
- Cognos TM1
- Power BI
- Oracle EPM
- Excel Corporate
- Workflow BPM

### Padrões
- API-first (OpenAPI 3.0)
- Eventos assíncronos onde couber
- Observabilidade (logs, métricas, tracing)
- Segurança em camadas (IAM, mTLS, criptografia em repouso e trânsito)
- LGPD by design
