**Case:** Modernização de Infraestrutura e Aplicação Cognos TM1  
**Fase:** 03-execucao  
**Documento:** Arquitetura Solucao

---

## Arquitetura Alvo
Ver `diagramas/` para diagrama detalhado.

### Componentes
- IBM Cognos TM1 v10.2 → v11 PAW
- Planning Analytics Workspace
- Windows Server 2012 → 2022
- SQL Server
- Active Directory
- Backup Veeam

### Padrões
- API-first (OpenAPI 3.0)
- Eventos assíncronos onde couber
- Observabilidade (logs, métricas, tracing)
- Segurança em camadas (IAM, mTLS, criptografia em repouso e trânsito)
- LGPD by design
