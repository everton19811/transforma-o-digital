**Case:** Migração de Plataforma Obsoleta de Planejamento para Google Cloud  
**Fase:** 01-iniciacao  
**Documento:** Business Case

---

## 1. Contexto
Sistema legado monolítico em servidor único, base Oracle 11g fora de suporte, integrações via arquivo TXT, sem DR, custo alto de sustentação.

## 2. Problema
Processos manuais, retrabalho, baixa rastreabilidade e riscos operacionais impactando a operação e a tomada de decisão.

## 3. Objetivo
Substituir plataforma legada de planejamento (on-premise, obsoleta e sem suporte) por solução moderna em Google Cloud (BigQuery + Looker + Cloud Run), garantindo governança, escalabilidade e redução de TCO em 35%.

## 4. Alternativas Avaliadas
| # | Alternativa | CAPEX | OPEX/ano | Prazo | Recomendada |
|---|-------------|-------|----------|-------|-------------|
| A | Manter As-Is | R$ 0 | Alto | — | Não |
| B | Reformar legado | Médio | Médio | 4m | Não |
| C | Solução alvo (**recomendada**) | R$ 4.500.000 | Baixo | 10 meses | **Sim** |

## 5. Benefícios Esperados
- Redução TCO: 35%
- Time-to-insight: dias → minutos
- Uptime: 97% → 99,95%
- Custo por consulta: -60%
- Cobertura de testes automatizados: 80%

## 6. Investimento
- Orçamento total: **R$ 4.500.000**
- Duração: **10 meses**
- Metodologia: **Agile Scaled (SAFe Essential) + PMBOK para governança**

## 7. Análise Financeira
- VPL (5 anos, TMA 12%): positivo
- Payback: 18 meses
- TIR: 28%

## 8. Recomendação
Aprovar a Alternativa C conforme escopo detalhado no Project Charter.
