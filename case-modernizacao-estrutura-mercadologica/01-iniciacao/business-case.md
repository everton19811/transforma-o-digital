**Case:** Modernização do Sistema de Estrutura Mercadológica (Low Platform)  
**Fase:** 01-iniciacao  
**Documento:** Business Case

---

## 1. Contexto
Estrutura mercadológica é o coração da precificação, sortimento e BI. Legado em AS400 com janela batch noturna, mudanças demoram 48h para refletir no PDV, alto risco operacional.

## 2. Problema
Processos manuais, retrabalho, baixa rastreabilidade e riscos operacionais impactando a operação e a tomada de decisão.

## 3. Objetivo
Substituir sistema legado de estrutura mercadológica (categorias, subcategorias, segmentos) em baixa plataforma (Cobol/AS400) por microserviços em nuvem, com API-first e sincronização em tempo real com ERP, PDV e e-commerce.

## 4. Alternativas Avaliadas
| # | Alternativa | CAPEX | OPEX/ano | Prazo | Recomendada |
|---|-------------|-------|----------|-------|-------------|
| A | Manter As-Is | R$ 0 | Alto | — | Não |
| B | Reformar legado | Médio | Médio | 4m | Não |
| C | Solução alvo (**recomendada**) | R$ 5.800.000 | Baixo | 12 meses | **Sim** |

## 5. Benefícios Esperados
- Latência de propagação: 48h → <5min
- Redução de incidentes de sortimento: -80%
- Cobertura API: 100% das operações
- Redução custo AS400: -70%
- Time-to-market de nova categoria: -65%

## 6. Investimento
- Orçamento total: **R$ 5.800.000**
- Duração: **12 meses**
- Metodologia: **Scrum + PMBOK (Strangler Fig Pattern)**

## 7. Análise Financeira
- VPL (5 anos, TMA 12%): positivo
- Payback: 18 meses
- TIR: 28%

## 8. Recomendação
Aprovar a Alternativa C conforme escopo detalhado no Project Charter.
