[README (1).md](https://github.com/user-attachments/files/30239994/README.1.md)
# 🚀 Portfólio de Cases — Transformação Digital

> Repositório de **cases de transformação digital** documentados sob a ótica do PMBOK + práticas ágeis híbridas. Cada pasta `case-*` é um projeto completo, autocontido, seguindo a **mesma estrutura padronizada** para facilitar consulta, comparação e reuso.

---

## 📂 Estrutura do Repositório

```text
📦 repositorio/
├── 📁 case-nome-do-projeto/          ← Case 1
│   ├── 01-iniciacao/
│   ├── 02-planejamento/
│   ├── 03-execucao/
│   ├── 04-monitoramento/
│   ├── 05-encerramento/
│   ├── diagramas/
│   └── README.md
│
└── 📁 case-nome-do-projeto/   ← Case N (mesma estrutura)
    └── ...
```

Todo case novo deve seguir **exatamente** este padrão de pastas — basta duplicar um existente, renomear e substituir o conteúdo.

---

## 🧭 O que tem em cada pasta

Cada case é organizado pelos **5 grupos de processos do PMBOK**, com foco em **modernização, integração e governança**:

| Pasta | Conteúdo típico |
|-------|-----------------|
| `01-iniciacao/` | Termo de Abertura (TAP/Charter), Registro de Stakeholders, Business Case, Visão de Arquitetura |
| `02-planejamento/` | Escopo, EAP/WBS, Cronograma, Orçamento, Matriz de Riscos, Plano de Integrações, Plano de Migração, Plano de Governança de Dados |
| `03-execucao/` | Atas de reunião, ADRs (Architecture Decision Records), Change Requests, Registros de deploy e cutover |
| `04-monitoramento/` | Status Reports, KPIs, EVM, Burndown, Dashboards, Log de Riscos e Incidentes |
| `05-encerramento/` | Termo de Aceite, Lições Aprendidas, Post-Mortem, Relatório Final, Handover Operacional |
| `diagramas/` | Gantt, EAP, Arquitetura, Fluxos de Integração e Mapas de Sistemas (em Mermaid.js — renderizados nativamente pelo GitHub) |
| `README.md` | Visão geral do case: contexto, problema, solução, arquitetura e resultados |

---

## 🚀 Como Navegar

1. **Escolha um case** na raiz do repositório.
2. **Leia o `README.md`** interno para entender contexto, desafio técnico e resultados.
3. **Explore as pastas numeradas** na ordem do ciclo de vida do projeto (01 → 05).
4. **Consulte `diagramas/`** para visualizar arquitetura, cronograma e fluxos de integração.
5. **Copie e adapte** qualquer artefato para seus próprios projetos.

---

## ➕ Como Adicionar um Novo Case

1. Duplique a pasta de um case existente: `cp -r case-migra2cloud case-novo-projeto`
2. Renomeie mantendo o prefixo `case-`.
3. Substitua o conteúdo dos documentos preservando a estrutura de pastas.
4. Atualize o `README.md` interno com o contexto do novo projeto.
5. Adicione o novo case à tabela abaixo.

---

## 📚 Cases Documentados

| Case | Setor | Metodologia | Status |
|------|-------|-------------|--------|
| [case-planejamento-orcamentario](./case-planejamento-orcamentario) | Reestruturação do ciclo orçamentário corporativo (TM1 + SAP) | Híbrido (PMBOK + Scrum) | ✅ Concluído |
| [case-modernizacao-cognos](./case-modernizacao-cognos) | Upgrade IBM Cognos TM1 (v10 → v11 PAW) e modernização de infraestrutura | Híbrido (PMBOK + Ágil) | ✅ Concluído |
| [case-migra2cloud](./case-migra2cloud) | Migração de plataforma obsoleta de planejamento para Google Cloud (BigQuery + Looker) | Híbrido (PMBOK + Scrum) | ✅ Concluído |
| [case-modernizacao-estrutura-mercadologica](./case-modernizacao-estrutura-mercadologica) | Modernização de sistema de estrutura mercadológica (AS400/Cobol → Cloud microservices) | Híbrido (PMBOK + Scrum) | ✅ Concluído |
| [case-docusign-fornecedor](./case-docusign-fornecedor) | Adoção de assinaturas digitais Docusign integradas ao SAP Ariba para contratos de fornecedores | Híbrido (PMBOK + Ágil) | ✅ Concluído |
| [case-ong-desenvolve](./case-ong-desenvolve) | CRM interno para controle de inscritos e evolução de alunos com governança LGPD (ONG Desenvolve no Espectro) | Híbrido (PMBOK + Scrum) | 🚧 Em execução |
| _(próximo case)_ | — | — | ⏳🔜 Em breve |

---

## 🎯 Objetivo do Portfólio

- Demonstrar **domínio em transformação digital** aplicada a projetos reais
- Servir como **biblioteca de artefatos reutilizáveis** para modernização e cloud
- Mostrar **consistência de documentação** entre projetos de complexidade e stacks distintos
- Evidenciar competências em **integrações corporativas, migração cloud e governança de dados**
- Facilitar **onboarding** e **transferência de conhecimento**

---

## 🛠️ Competências Demonstradas

- **Modernização de legados**: AS400, Cobol, TM1 v10 → arquiteturas cloud-native
- **Cloud & Dados**: Google Cloud, BigQuery, Looker, ETL, Data Governance
- **Integrações corporativas**: SAP, Ariba, Docusign, APIs, microservices
- **Governança**: LGPD, ITIL, gestão de mudança, controle de fornecedores
- **Gestão híbrida**: PMBOK + Scrum + Kanban + EVM

---

## 📬 Contato

- 💼 [LinkedIn](https://www.linkedin.com/in/everton19811)
- 📧 everton19811@gmail.com
- 💬 [WhatsApp](https://wa.me/5511967413787?text=Ol%C3%A1%20Everton%2C%20vim%20pelo%20seu%20GitHub!)
- 🐙 [GitHub](https://github.com/everton19811)

---

⭐ Se este material foi útil, deixe uma estrela no repositório!
