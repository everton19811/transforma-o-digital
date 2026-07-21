**Case:** Migração de Plataforma Obsoleta de Planejamento para Google Cloud  
**Fase:** 01-iniciacao  
**Documento:** Project Charter

---

## 1. Identificação
- **Nome:** Migração de Plataforma Obsoleta de Planejamento para Google Cloud
- **Sponsor:** Diretoria Executiva
- **Gerente de Projetos:** Everton Silva
- **Duração:** 10 meses
- **Orçamento:** R$ 4.500.000

## 2. Justificativa
Sistema legado monolítico em servidor único, base Oracle 11g fora de suporte, integrações via arquivo TXT, sem DR, custo alto de sustentação.

## 3. Objetivo SMART
Substituir plataforma legada de planejamento (on-premise, obsoleta e sem suporte) por solução moderna em Google Cloud (BigQuery + Looker + Cloud Run), garantindo governança, escalabilidade e redução de TCO em 35%.

## 4. Escopo
### Incluso
- Levantamento AS-IS e desenho TO-BE
- Implantação da solução alvo
- Integrações com sistemas: Google Cloud (BigQuery, Cloud Run, Cloud Storage, Pub/Sub), Looker, Dataflow, Cloud Composer (Airflow), Terraform, GitHub Actions, Legado Oracle 11g, SAP
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
- Redução TCO: 35%
- Time-to-insight: dias → minutos
- Uptime: 97% → 99,95%
- Custo por consulta: -60%
- Cobertura de testes automatizados: 80%

## 8. Aprovações
| Papel | Nome | Data | Assinatura |
|-------|------|------|------------|
| Sponsor | — | — | — |
| PMO | — | — | — |
| GP | Everton Silva | — | — |
