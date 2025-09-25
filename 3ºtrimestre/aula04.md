# 🛠️ Capítulo 4 — **Ferramentas Específicas por Área**

![badge](https://img.shields.io/badge/Trimestre-3º-blue) ![badge](https://img.shields.io/badge/Carga%20estimada-4~6%20aulas-brightgreen) ![badge](https://img.shields.io/badge/Nível-Intermediário%2FAvançando-orange) ![badge](https://img.shields.io/badge/Foco-UC24%20|%20Tecnologia%20e%20Trabalho-purple)

> ✨ **Frase motivadora**
> “Ferramentas são multiplicadores de capacidade. O valor nasce quando pessoas, processos e tecnologia se alinham.” — _IAra_

---

## 🎯 Objetivos de Aprendizagem

- Mapear **ferramentas digitais por setor** (Educação, Administração/Finanças, Marketing, Saúde, Engenharia/Arquitetura, TI/Desenvolvimento, Vendas/Atendimento).
- Definir **critérios técnicos e de negócio** para seleção (funcionais, segurança/LGPD, integração, custo total – TCO).
- Planejar **implantação e governança** (políticas de uso, perfis de acesso, auditoria, backup, trilhas de capacitação).
- Produzir **entregáveis práticos** (matriz de decisão, canvas de requisitos, plano de rollout, templates e checklists).

---

## 🧭 Introdução Didática

Cada área profissional utiliza um conjunto específico de ferramentas para **ganhar eficiência**, **qualidade** e **rastreabilidade**. Porém, **escolher “a melhor ferramenta”** não é apenas comparar marcas: é garantir **aderência ao processo**, **segurança da informação**, **interoperabilidade** e **custo sustentável**.
Neste capítulo, você verá **mapas por área**, **padrões abertos por domínio**, **critérios de escolha** e **modelos prontos** para aplicar na prática.

---

## 1) 🗺️ Mapa Geral — **Áreas x Ferramentas x Entregáveis**

| Área                            | Ferramentas típicas                                                                      | Entregáveis do dia a dia                                 | Métricas (KPIs)                                            |
| ------------------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------- | ---------------------------------------------------------- |
| **Educação (LMS/Autores)**      | LMS (Classroom/Moodle), formulários, videoconf., bancos de rubricas, autoria de conteúdo | Plano de aula, trilhas, avaliações, rubricas, relatórios | Entrega de atividades, nota média, engajamento, presença   |
| **Admin/Finanças (ERP)**        | Planilhas avançadas, ERP, emissão de notas, conciliação, BI                              | Fluxo de caixa, DRE simpl., relatórios, contratos        | Prazo de pagamento, inadimplência, acurácia de lançamentos |
| **Marketing (MarTech)**         | Automação, social media, analytics, DAM, SEO                                             | Calendário editorial, campanhas, peças, relatórios       | Alcance, CTR, conversão, CAC, ROI                          |
| **Saúde (PEP/Telemedicina)**    | Prontuário eletrônico (PEP), agendamento, teleconsulta, PACS                             | Evoluções, atestados, receituários, laudos               | Tempo de atendimento, taxa de retorno, índice de adesão    |
| **Eng./Arq. (CAD/BIM/GIS)**     | CAD, BIM (4D/5D), compatibilização, QGIS, gerenciamento                                  | Plantas/modelos, memoriais, orçamentos, cronogramas      | Retrabalho por conflito, avanço físico, var. custo/prazo   |
| **TI/Dev (DevOps)**             | Repositórios, CI/CD, rastreio de issues, observabilidade                                 | Releases, documentação, testes, incidentes               | Lead time de mudança, falhas em produção, MTTR             |
| **Vendas/Atendimento (CRM/CS)** | CRM, chat/voz, base de conhecimento, NPS/CSAT                                            | Oportunidades, propostas, SLA, FAQs                      | Taxa de ganho, tempo de 1ª resposta, NPS/CSAT              |

> ℹ️ **Exemplos de marcas são apenas ilustrações**; foque nos **requisitos e padrões**.

---

## 2) 🎓 Educação — **LMS, Avaliação e Acessibilidade**

**Fluxo típico:** planejamento → conteúdo → atividade → avaliação → feedback → relatório.
**Requisitos-chave:**

- **Acessibilidade (WCAG)**: legendas, leitor de tela, contraste, _alt text_.
- **Integração**: LTI/SCORM/xAPI (intercâmbio de cursos e notas).
- **Avaliação**: rubricas, bancos de itens, randomização, analytics de aprendizagem.
- **Privacidade**: perfis (aluno/professor/coord.), consentimento para gravações, retenção de dados.

**Boas práticas**

- Rubricas claras (critérios + níveis).
- Trilhas com **prérequisitos** e **prazos** visíveis.
- Banco de questões por **competência**.
- **Feedback multimídia** breve e objetivo.

---

## 3) 💼 Administração & Finanças — **ERP/BI e Conformidade**

**Fluxo típico:** lançamento → conciliação → análise → relatório → decisão.
**Requisitos-chave:**

- **Conciliação bancária** e importação (OFX/CNAB).
- **Compliance fiscal** (notas, retenções) e trilhas de auditoria.
- **BI**: dashboards de caixa, DRE simplificada, metas e alertas.
- **Segurança**: papéis (RBAC), seg. por centro de custo, logs e backups.

**Boas práticas**

- Plano de contas padronizado e **centros de custo**.
- **Fechamento periódico** (semanal/mensal) com checklist.
- Políticas de **documentação fiscal** e retenção.

---

## 4) 📣 Marketing — **Automação, Conteúdo e Métricas**

**Fluxo típico:** pesquisa → calendário → produção → aprovação → publicação → mensuração.
**Requisitos-chave:**

- **Automação** (nutrição, segmentação, webhooks).
- **DAM** (biblioteca de mídias) com metadados e direitos.
- **Analytics** (UTM/GA4) e painéis de conversão.
- **SEO** on-page/off-page e monitoramento de reputação.

**Boas práticas**

- **Briefing padrão** por campanha.
- Controle de **versões** de peças e **aprovação** formal.
- **Guia de tom de voz** e manual de marca.

---

## 5) 🏥 Saúde — **PEP, Telemedicina e Padrões Clínicos**

**Fluxo típico:** agendamento → consulta → evolução → prescrição/laudo → faturamento.
**Requisitos-chave:**

- **PEP** com controle de acesso (sigilo médico).
- **Teleconsulta** com consentimento e registro.
- **Padrões**: HL7/FHIR (dados clínicos), DICOM (imagens), CID-10 (classificação).
- **LGPD**: base legal, minimização, logs de acesso, política de retenção.

**Boas práticas**

- Modelos de evolução e **chelists de segurança**.
- Protocolos de **backup criptografado** e **contingência**.
- Trilhas de **auditoria** e revisão periódica de acessos.

---

## 6) 🏗️ Engenharia/Arquitetura — **CAD/BIM/GIS e Compatibilização**

**Fluxo típico:** estudo preliminar → anteprojeto → projeto executivo → obra → _as built_.
**Requisitos-chave:**

- **CAD/BIM** (IFC/ISO 19650), 4D (tempo) e 5D (custos).
- **Revisões e _clash detection_** (compatibilização).
- **GIS** para mapas e análises territoriais.
- **Integrações** com orçamento (ERP) e cronograma (MSP/Primavera).

**Boas práticas**

- Padrões de **nomenclatura** de camadas/objetos.
- Bibliotecas de **famílias/componentes** validadas.
- Relatórios de **interferências** com plano de ação.

---

## 7) 👨‍💻 TI/Desenvolvimento — **Código, Qualidade e Operações**

**Fluxo típico:** planejamento → desenvolvimento → testes → _release_ → observabilidade.
**Requisitos-chave:**

- **Repositórios** (controle de versão), _code review_, _branching_.
- **CI/CD**: _build_, teste, _deploy_ automatizados.
- **Observabilidade**: logs, métricas, _tracing_, alertas.
- **Segurança**: scanner de dependências, segredos, RBAC, backups.

**Boas práticas**

- **Documentação viva** (README, ADRs, _changelogs_).
- _Feature flags_ e **rollback** seguro.
- SLO/SLA/SLI e **pós-mortem** sem culpados.

---

## 8) 🧩 Vendas/Atendimento — **CRM, SLA e Base de Conhecimento**

**Fluxo típico:** prospecção → qualificação → proposta → fechamento → pós-venda.
**Requisitos-chave:**

- **CRM** com funil, atividades, propostas e integrações (e-mail/voz/chat).
- **SLA** (1ª resposta, resolução) e indicadores de satisfação (CSAT/NPS).
- **Base de conhecimento/FAQ** e **templates** de resposta.
- **LGPD**: consentimento, opt-in/out, gestão de preferências.

**Boas práticas**

- **Playbooks** por etapa do funil.
- Modelos de **proposta** e **contrato** padronizados.
- Pesquisa de satisfação **pós-atendimento**.

---

## 9) 🔗 Integração, Automatização e Dados

- **APIs & Webhooks**: trocas em tempo real (REST/JSON; GraphQL quando fizer sentido).
- **ETL/ELT**: consolidar dados em _data marts_ para BI.
- **Orquestração & automação**: gatilhos entre sistemas (ex.: formulário → CRM → e-mail → tarefa).
- **Catálogo de dados**: dicionário, donos, qualidade, classificação (público/interno/restrito).

---

## 10) 🛡️ Segurança, LGPD e Governança de Acesso

- **Princípio do menor privilégio** (RBAC/ABAC) e **revisão trimestral** de acessos.
- **Criptografia** em repouso e em trânsito; **2FA/MFA** e gerenciador de senhas.
- **Backups** 3-2-1 testados; plano de **continuidade** e **resposta a incidentes**.
- **RIPD (Relatório de Impacto à Proteção de Dados)** para processos sensíveis.
- **Logs e trilhas de auditoria** (quem viu/alterou o quê e quando).

---

## 11) 🧪 Como escolher ferramentas — **Canvas de Requisitos + Matriz de Decisão**

### 11.1 Canvas de Requisitos (template)

```
Problema/Objetivo:
Usuários e Perfis:
Processo atual (AS-IS):
Processo desejado (TO-BE):
Requisitos Funcionais (Top 10):
Requisitos Não Funcionais (Segurança, Desempenho, Acessibilidade, Integrações):
Conformidades (LGPD, padrões do domínio):
Critérios de Sucesso (KPIs):
Riscos e Mitigações:
Treinamento e Suporte:
```

### 11.2 Matriz de Decisão Ponderada (exemplo)

| Critério                              | Peso |  Opção A |  Opção B |  Opção C |
| ------------------------------------- | ---: | -------: | -------: | -------: |
| Aderência funcional                   | 0,30 |        8 |        9 |        7 |
| Integração & APIs                     | 0,20 |        7 |        8 |        6 |
| Segurança & LGPD                      | 0,20 |        9 |        8 |        8 |
| Usabilidade & Acessibilidade          | 0,15 |        8 |        7 |        9 |
| TCO (licença + implantação + suporte) | 0,15 |        7 |        8 |        9 |
| **Score (∑peso×nota)**                | 1,00 | **7,95** | **8,20** | **7,65** |

> 💡 **TCO**: considere licença, implantação, migração de dados, treinamento, tempo de equipe, suporte e evolução.

---

## 12) 🚀 Implantação — **5 fases e entregáveis**

1. **Descoberta** (imersão, _as-is/to-be_, canvas, riscos) → _Relatório de diagnóstico_.
2. **Prova de Conceito (PoC)** (usuários-chave, dados de teste, critérios) → _Relatório de validação_.
3. **Rollout Piloto** (turma/setor) → _Plano de comunicação e suporte_.
4. **Escala** (migração, perfis, integrações) → _Checklists de segurança_ e _treinamentos_.
5. **Operação** (SLA, monitoramento, auditoria) → _Painel de KPIs_ e _retro contínua_.

---

## 13) 🧩 Estudos de Caso (mini-cenários)

- **Escola técnica**: adota LMS com trilhas por UC; integra formulários → planilhas → BI; resultado: +25% de entrega no prazo.
- **Clínica**: telemedicina + PEP com FHIR/DICOM; criptografia e revisão de acessos; resultado: -30% no tempo de espera.
- **Construtora**: BIM com IFC e compatibilização; dashboard de obra; resultado: -20% de retrabalho por interferência.

---

## 🧪 Atividades Práticas (sala & casa)

1. **Canvas de requisitos**: escolha uma área e preencha o template (máx. 1 página).
2. **Matriz de decisão**: compare 3 opções (podem ser genéricas) e apresente o **score**.
3. **Plano de rollout**: defina público, cronograma, riscos, comunicação e KPIs.
4. **Política de acesso**: descreva papéis, permissões, revisão e logs.
5. **Checklist LGPD**: finalidade, base legal, minimização, retenção, consentimento (se aplicável), direitos do titular.

---

## 🎓 Conclusão

Ferramentas **não resolvem sozinhas**: elas **potencializam processos bem desenhados** e **pessoas capacitadas**. Ao dominar requisitos, padrões do domínio, segurança e implantação, você passa a **liderar escolhas tecnológicas** com visão crítica e responsabilidade.

---

# 🧠 Fixação de Conteúdo

### ✅ 1) Dissertativas

1. Elabore um **plano de implantação** para uma ferramenta de sua área (Educação, Saúde, etc.), incluindo riscos e KPIs.
2. Explique como **padrões abertos** (por ex., LTI/SCORM, FHIR/HL7, IFC/ISO 19650) reduzem **custos de integração** e **lock-in**.

---

### 🔘 2) Múltipla Escolha (uma correta)

1. Em **saúde**, o padrão para **interoperabilidade de dados clínicos** é:

   - [ ] SCORM
   - [ ] IFC
   - [ ] FHIR
   - [ ] GA4

2. Em **educação**, para **portabilidade de cursos e notas**, são comuns:

   - [ ] DICOM e HL7
   - [ ] LTI/SCORM/xAPI
   - [ ] OFX e CNAB
   - [ ] ITIL

3. Em **BIM**, o formato de **intercâmbio** recomendado é:

   - [ ] UTM
   - [ ] IFC
   - [ ] CSV
   - [ ] PDF

---

### ☐ 3) Caixa de Seleção (múltiplas corretas)

1. São **critérios não funcionais** relevantes na escolha de ferramentas:

   - [ ] Aderência LGPD
   - [ ] Disponibilidade e desempenho
   - [ ] Paleta de cores do logo
   - [ ] Acessibilidade (WCAG)
   - [ ] APIs e webhooks
   - [ ] Nome “da moda”

---

### 🔗 4) Associação de Colunas

Associe **padrão** ao **domínio**:

| Padrão         | Domínio             |
| -------------- | ------------------- |
| SCORM/LTI/xAPI | Educação            |
| FHIR/HL7       | Saúde               |
| DICOM          | Imagens médicas     |
| IFC/ISO 19650  | BIM/Construção      |
| OFX/CNAB       | Financeiro/Bancário |

---

### ✔️ 5) Verdadeiro ou Falso (quatro sentenças + alternativas)

a) TCO inclui custos de licença, implantação, treinamento e suporte.
b) Padrões abertos diminuem dependência de fornecedor.
c) PoC é desnecessária quando a marca é famosa.
d) RBAC/ABAC ajudam na governança de acessos.

- [ ] F V V V
- [ ] V F V V
- [ ] V F F V
- [ ] F V F V

---

### 🚀 6) Desafio (síntese e aplicação)

Monte um **dossiê de seleção** (2 páginas) para uma ferramenta da sua área com:

- Canvas de requisitos preenchido;
- Matriz de decisão com pesos/notes;
- Plano de rollout em 5 fases;
- Política de acesso e checklist LGPD;
- 3 KPIs de adoção e 3 de desempenho.

---

## 📚 Referências Complementares (sugeridas)

- Documentos introdutórios de **SCORM/LTI/xAPI**, **IFC/ISO 19650**, **FHIR/HL7/DICOM**.
- Guias de **TCO** e **matriz de decisão** em projetos de TI.
- Materiais de **governança de dados**, **acessibilidade digital (WCAG)** e **segurança**.

---

> 💬 **Próximo capítulo (5):** _Segurança da Informação no Cotidiano_ — integraremos políticas de acesso, criptografia, backups, auditoria, resposta a incidentes e LGPD no uso diário das ferramentas.
