**Case:** Modernização de Infraestrutura e Aplicação Cognos TM1  
**Fase:** 01-iniciacao  
**Documento:** Project Charter

---

## 1. Identificação
- **Nome:** Modernização de Infraestrutura e Aplicação Cognos TM1
- **Sponsor:** Diretoria Executiva
- **Gerente de Projetos:** Everton Silva
- **Duração:** 6 meses
- **Orçamento:** R$ 1.850.000

## 2. Justificativa
Ambiente TM1 legado (v10.2) em servidores em fim de vida, cubos com regras complexas e feeders mal dimensionados, janelas de contingência frágeis e tempo de recálculo acima de SLA.

## 3. Objetivo SMART
Modernizar a plataforma IBM Cognos TM1 (upgrade de versão + migração para servidores robustos + refatoração de cubos e regras) garantindo alta disponibilidade, performance e sustentação da operação de Planejamento.

## 4. Escopo
### Incluso
- Levantamento AS-IS e desenho TO-BE
- Implantação da solução alvo
- Integrações com sistemas: IBM Cognos TM1 v10.2 → v11 PAW, Planning Analytics Workspace, Windows Server 2012 → 2022, SQL Server, Active Directory, Backup Veeam
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
- Tempo de recálculo de cubos: -60%
- Disponibilidade: 99,2% → 99,9%
- Redução de incidentes P1/P2: -70%
- Janela de backup: 6h → 1h30

## 8. Aprovações
| Papel | Nome | Data | Assinatura |
|-------|------|------|------------|
| Sponsor | — | — | — |
| PMO | — | — | — |
| GP | Everton Silva | — | — |
