# 🛡️ Capítulo 5 — **Segurança da Informação no Cotidiano Profissional**

![badge](https://img.shields.io/badge/Trimestre-3º-blue) ![badge](https://img.shields.io/badge/Carga%20estimada-4~6%20aulas-brightgreen) ![badge](https://img.shields.io/badge/Nível-Intermediário%2FAvançado-orange) ![badge](https://img.shields.io/badge/Foco-UC24%20|%20Tecnologia%20e%20Trabalho-purple)

> ✨ **Frase motivadora**
> “A segurança não é um produto, é um processo.” — _Bruce Schneier_

---

## 🎯 Objetivos de Aprendizagem

- Entender os **fundamentos** de Segurança da Informação (Confidencialidade, Integridade e Disponibilidade – **CID**).
- Aplicar **boas práticas** no dia a dia: senhas, 2FA/MFA, atualizações, backup, compartilhamento seguro.
- Diferenciar **ameaças comuns** (phishing, malware, engenharia social) e executar **respostas rápidas**.
- Modelar **controle de acesso** (RBAC/ABAC), **cripto** (em repouso/em trânsito), **logs e auditoria**.
- Cumprir no cotidiano princípios de **LGPD** (finalidade, minimização, base legal, direitos do titular).

---

## 🧭 Introdução Didática

Segurança da Informação não é “coisa do time de TI”; é **competência de todo profissional**. Um clique em link malicioso, uma planilha aberta ao público ou um backup que não restaura podem parar operações inteiras. Este capítulo transforma **conceitos** em **rotinas praticáveis** para proteger pessoas, dados e resultados.

---

## 1) 🔺 Fundamentos: CIA (CID) e princípios práticos

- **Confidencialidade (C)**: só quem **deve** acessa. _Como:_ controle de acesso, criptografia, classificação.
- **Integridade (I)**: dado **íntegro e não alterado** indevidamente. _Como:_ hash, trilhas de auditoria, revisão.
- **Disponibilidade (D)**: dado **acessível quando necessário**. _Como:_ backup, redundância, planos de continuidade.

**Princípios operacionais**:

- **Menor Privilégio** (least privilege), **Necessidade de Saber** (need-to-know), **Separação de Funções**, **Defesa em Camadas**.

---

## 2) 🧑‍💻 Higiene Digital Pessoal (o básico bem feito)

### 2.1 Senhas e MFA

- Frases-senha (≥12 caracteres) + **MFA/2FA** em tudo que for possível.
- **Gerenciador de senhas** (evite bloco de notas/print).
- **Nunca** reutilize senha entre serviços.

### 2.2 Atualizações e hardening

- **Sistema e apps atualizados** (auto-update).
- **Bloqueio de tela** (PIN/senha/biometria).
- Desative **instalações de fontes desconhecidas**; cuidado com extensões.

### 2.3 Compartilhamento consciente

- **Links com expiração** e **apenas leitura** quando couber.
- Revise permissões **mensalmente** (quem vê o quê).
- Evite dados sensíveis em **grupos abertos** (chat/e-mail).

---

## 3) 🕵️‍♀️ Ameaças do dia a dia e como reagir

### 3.1 Phishing (e variações)

- **Sinais**: urgência, erro de ortografia, remetente estranho, link encurtado/QR (**quishing**).
- **Ação**: não clique; **passe o mouse** e confira o domínio; valide por canal alternativo; reporte.

### 3.2 Malware / Ransomware

- **Sinais**: lentidão súbita, arquivos criptografados, pedidos de resgate.
- **Ação**: desconectar da rede, informar TI, **não** pagar resgate, acionar **plano de resposta**.

### 3.3 Engenharia Social / Deepfakes

- **Sinais**: “é o diretor pedindo transferência urgente”, “troca de conta bancária de fornecedor”.
- **Ação**: política de **verificação em dois canais** (telefone oficial + e-mail institucional).

> 🧭 **Regra de ouro**: quando houver **dinheiro, dados ou urgência**, **pare e valide**.

---

## 4) 🗂️ Classificação de Dados e Compartilhamento

| Classe           | Exemplos                         | Regra de Acesso               | Armazenamento                     |
| ---------------- | -------------------------------- | ----------------------------- | --------------------------------- |
| **Público**      | Material de divulgação           | Livre                         | Site/Drive público                |
| **Interno**      | Atas, planos, checklists         | Time/Escola                   | Drive com permissão por grupo     |
| **Confidencial** | Dados pessoais, notas, contratos | Menor privilégio (RBAC/ABAC)  | Pasta restrita + criptografia     |
| **Sigiloso**     | Saúde/financeiro sensível        | Acesso excepcional, auditoria | Cofre de dados/criptografia forte |

- **Política**: cada arquivo deve ter **classe + responsável + prazo de retenção**.

---

## 5) 🔑 Controle de Acesso (RBAC/ABAC) e auditoria

- **RBAC** (por **papéis**): aluno, professor, coord., financeiro. Fácil de gerir.
- **ABAC** (por **atributos**): horário, local, tipo de dispositivo, classificação do dado. Flexível e granular.
- **Trilhas de auditoria**: _quem acessou/alterou o quê e quando_.
- **Revisão trimestral** de acessos e **desprovisionamento** ao sair do time.

---

## 6) 🔒 Criptografia em repouso e em trânsito

- **Em trânsito**: **TLS 1.3** (https, VPN).
- **Em repouso**: criptografia de disco/pasta/arquivo (**AES-256** é comum).
- **Chaves e segredos**: nunca em planilhas abertas ou repositórios; use **cofre** (secret manager).
- **E-mail**: prefira link seguro; se anexar, **senha separada** (outro canal).

---

## 7) 💾 Backup, Restore e Continuidade (3-2-1)

- **3 cópias** (produtiva + 2 cópias), **2 mídias** diferentes, **1 off-site** (nuvem segura).
- **Rotina**: diário/semana, **testes de restauração** mensais.
- **Plano de continuidade**: prioridades (RTO/RPO), responsáveis, contatos, checklists.

**Mini-roteiro de teste de restore** (30–60 min):

1. Escolher arquivo aleatório crítico → 2) Restaurar → 3) Verificar integridade → 4) Registrar evidência.

---

## 8) ☁️ Nuvem, Dispositivos e Redes

- **Modelo de responsabilidade compartilhada** (SaaS/IaaS): provedor cuida da infraestrutura, **você cuida de contas, dados e permissões**.
- **Wi-Fi**: WPA2/3, senha forte, evitar redes abertas; para remoto, **VPN**.
- **BYOD/MDM**: se usar dispositivo pessoal, exigir **MFA, bloqueio, criptografia, atualização**; defina **política** (o que pode/Não pode).

---

## 9) 🧩 LGPD no cotidiano (versão prática)

- **Base legal** clara (ex.: execução de contrato, cumprimento legal, consentimento).
- **Princípios**: finalidade, adequação, **minimização**, qualidade, segurança, responsabilização.
- **Direitos do titular**: acesso, correção, portabilidade, revogação, eliminação quando cabível.
- **RIPD** (Relatório de Impacto): descreve riscos e medidas (use em processos **sensíveis**).
- **Compartilhamento com IA**: **não** enviar dados pessoais/sensíveis sem base legal e anonimização.

---

## 10) 🆘 Resposta a Incidentes (playbook de bolso)

1. **Detectar**: sinais/alertas (usuário, antivírus, SIEM).
2. **Conter**: isolar dispositivo/conta, revogar tokens, trocar senhas.
3. **Erradicar**: remover causa raiz (malware, credencial vazada).
4. **Restaurar**: sistemas/dados a partir de backup validado.
5. **Aprender**: pós-incidente (lições, políticas, treinamento).
6. **Comunicar**: conforme políticas/LGPD (quando aplicável).

---

## 11) ✅ Checklists Essenciais

**Check de Usuário (semanal)**

- [ ] 2FA em e-mail, drive e sistemas críticos
- [ ] Atualizações aplicadas
- [ ] Pastas compartilhadas revisadas
- [ ] Backup pessoal testado
- [ ] Caixa de entrada livre de anexos sensíveis

**Check de Time (mensal)**

- [ ] Revisão de acessos (entradas/saídas)
- [ ] Amostra de **logs/auditoria** verificada
- [ ] Teste de **restore** documentado
- [ ] Simulado rápido de **phishing** (cartilha educativa)
- [ ] Atualização de **RIPD** (se houver mudança de processo)

---

## 12) 📚 Modelos e Templates (prontos para copiar)

### 12.1 **Política de Classificação** (1 parágrafo)

> “Todos os documentos devem indicar classe (Público/Interno/Confidencial/Sigiloso), responsável, local de armazenamento e prazo de retenção. O acesso seguirá menor privilégio e será revisto trimestralmente.”

### 12.2 **Aviso de Confidencialidade (rodapé de e-mail)**

> “Esta mensagem e seus anexos são de uso interno e podem conter informações confidenciais. Se você não é o destinatário, apague e avise o remetente. É proibida sua divulgação sem autorização.”

### 12.3 **Procedimento de Incidente (resumo)**

> “Ao suspeitar de incidente: (1) isole o dispositivo/conta, (2) avise a coordenação/TI, (3) registre evidências (prints, hora), (4) aguarde instruções, (5) não apague vestígios.”

---

## 13) 🧪 Atividades Práticas (sala & casa)

1. **Ative 2FA** em 3 serviços e gere **comprovantes** (prints/registro).
2. **Revisão de compartilhamentos**: liste 10 arquivos que você possui; ajuste permissões e **classifique** cada um.
3. **Teste de restore**: realize a restauração de 1 arquivo e preencha uma **ficha de evidência** (data, hash opcional, verificação).
4. **Mini-RIPD**: escolha um processo com dados pessoais (ex.: listas de presença) e descreva **riscos e salvaguardas** (½ página).
5. **Simulado anti-phishing**: monte um **cartaz/infográfico** com 8 sinais de alerta + QR seguro para cartilha.

---

## 🎓 Conclusão

Segurança efetiva nasce de **hábitos simples, consistentes e verificáveis**. Ao cuidar de senhas, 2FA, backups, compartilhamentos e respostas a incidentes, você protege **pessoas**, **dados** e **projetos** — e se posiciona como um profissional confiável e valioso no mercado.

---

# 🧠 Fixação de Conteúdo

### ✅ 1) Dissertativas

1. Explique como **CID (Confidencialidade, Integridade, Disponibilidade)** orienta decisões cotidianas (ex.: compartilhamento, backup, auditoria).
2. Proponha um **playbook de resposta a phishing** para sua turma/equipe (5 passos claros).

---

### 🔘 2) Múltipla Escolha (uma correta)

1. O **princípio do menor privilégio** busca:

   - [ ] Simplificar nomes de arquivos
   - [ ] Dar acesso amplo para agilizar
   - [ ] Garantir acesso **apenas ao necessário**
   - [ ] Remover logs de auditoria

2. **Backup 3-2-1** significa:

   - [ ] 3 cópias, 2 mídias, 1 off-site
   - [ ] 3 cópias, 2 pastas, 1 senha
   - [ ] 3 cópias em nuvem
   - [ ] 2 cópias e 1 impressa

3. Em **criptografia**, proteger “em trânsito” significa:

   - [ ] Arquivo zipado
   - [ ] Conexão com **TLS/https**
   - [ ] Senha forte
   - [ ] Backup em HD externo

---

### ☐ 3) Caixa de Seleção (múltiplas corretas)

1. São **boas práticas** de segurança cotidiana:

   - [ ] 2FA/MFA
   - [ ] Revisão periódica de permissões
   - [ ] Reaproveitar senhas
   - [ ] Links com expiração
   - [ ] Enviar planilhas sensíveis por grupos abertos
   - [ ] Testar restore

---

### 🔗 4) Associação de Colunas

Associe o **termo** ao **conceito**:

| Termo    | Conceito                                 |
| -------- | ---------------------------------------- |
| RBAC     | Acesso por papéis                        |
| ABAC     | Acesso por atributos                     |
| Hash     | Verifica integridade                     |
| RIPD     | Relatório de impacto à proteção de dados |
| Quishing | Phishing por QR code                     |

---

### ✔️ 5) Verdadeiro ou Falso (quatro sentenças + alternativas)

a) Deepfakes podem ser usados em golpes de engenharia social.
b) Logs e trilhas de auditoria ajudam a detectar e investigar incidentes.
c) Modelo de responsabilidade compartilhada dispensa controle de permissões do cliente.
d) Classificação de dados orienta quem pode acessar e por quanto tempo reter.

- [ ] F V V V
- [ ] V F V V
- [ ] V F F V
- [ ] F V F V

---

### 🚀 6) Desafio (síntese e aplicação)

Crie o **Guia de Segurança da Turma/Equipe (1 página)** com:

- Política de **senhas + 2FA**;
- **Classificação de dados** + exemplos;
- **Procedimento de incidente** (fluxo de 6 passos);
- **Plano 3-2-1** com periodicidade e responsáveis;
- **Checklist mensal** de segurança e LGPD.

---

## 📚 Referências Complementares (sugeridas)

- Cartilhas introdutórias de **Segurança da Informação** e **Boas Práticas de e-mail**.
- Materiais sobre **LGPD** (conceitos e direitos do titular).
- Guias de **backup 3-2-1** e **resposta a incidentes**.
- Documentação sobre **controle de acesso** (RBAC/ABAC) e **criptografia** (TLS/AES).

---

> 💬 **Próximo capítulo (6):** _Visualização de Dados e Tomada de Decisão_ — tipos de gráficos, dashboards e infográficos profissionais, aplicando boas práticas e ética (evitando vieses e “mentiras” com gráficos).
