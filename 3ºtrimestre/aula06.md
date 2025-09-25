# 📊 Capítulo 6 — **Visualização de Dados e Tomada de Decisão**

![badge](https://img.shields.io/badge/Trimestre-3º-blue) ![badge](https://img.shields.io/badge/Carga%20estimada-5~6%20aulas-brightgreen) ![badge](https://img.shields.io/badge/Nível-Avançado-red) ![badge](https://img.shields.io/badge/Foco-UC24%20|%20Tecnologia%20e%20Trabalho-purple)

> ✨ **Frase motivadora**
> “Sem dados, você é apenas mais uma pessoa com opinião.” — _W. Edwards Deming_

---

## 🎯 Objetivos de Aprendizagem

- Entender a **importância estratégica** da visualização de dados no cotidiano profissional.
- Dominar os **tipos de gráficos** e suas aplicações (barra, linha, pizza, dispersão, mapas, radar, etc.).
- Criar **dashboards e infográficos** que transformem dados em decisões claras.
- Usar ferramentas de **visualização (Excel, Power BI, Google Data Studio, Tableau, Python/Matplotlib, etc.)**.
- Reconhecer e evitar **más práticas de visualização** (viés, gráficos enganosos, excesso de elementos).
- Aplicar princípios de **ética e LGPD** na exposição de informações.

---

## 🧭 Introdução Didática

Vivemos a **era dos dados**: relatórios, métricas, indicadores e dashboards estão em todos os setores. Mas dados **sozinhos** não dizem nada. Precisamos **transformá-los em histórias visuais** que permitam decisões rápidas, objetivas e corretas.
Este capítulo mostra **como escolher o gráfico certo**, **como montar um dashboard eficaz** e **como comunicar dados com clareza e ética**.

---

## 1) 📌 Por que visualizar dados?

- **Comunicação rápida**: gráficos condensam informações complexas.
- **Identificação de padrões**: tendências, sazonalidades, correlações.
- **Tomada de decisão**: apoio a gestores, equipes e projetos.
- **Engajamento**: apresentações mais atrativas e convincentes.
- **Inclusão**: recursos visuais ajudam diferentes perfis de público.

Ex.: em uma reunião de marketing, **mostrar** um gráfico de barras sobre conversões é mais eficaz do que **ler** 30 números de uma tabela.

---

## 2) 📊 Tipos de Gráficos e Seus Usos

### 2.1 Comparação

- **Barras**: comparar categorias (ex.: vendas por produto).
- **Colunas**: comparar valores ao longo do tempo.
- **Radar**: comparar múltiplas variáveis em escala comum.

### 2.2 Tendência

- **Linhas**: evolução temporal (ex.: crescimento mensal de acessos).
- **Área**: evolução acumulada.

### 2.3 Proporção

- **Pizza**: partes de um todo (máx. 5–6 categorias).
- **Barras empilhadas**: melhor que pizza para comparações.

### 2.4 Distribuição

- **Dispersão**: relação entre duas variáveis (ex.: horas de estudo × nota).
- **Boxplot**: distribuição, mediana, outliers.

### 2.5 Geoespacial

- **Mapas de calor**: intensidade por região.
- **Mapas georreferenciados**: dados sobre geolocalização (Google Maps/QGIS).

### 2.6 Especializados

- **Histograma**: frequência de valores (ex.: idade dos clientes).
- **Gráfico de bolha**: 3 variáveis (x, y, tamanho da bolha).
- **Bullet chart**: metas e desempenho.
- **Treemap**: hierarquias (ex.: participação por setor).

---

## 3) 🎨 Boas práticas de visualização

- **Clareza**: título direto, legendas curtas, evitar jargões.
- **Relevância**: mostrar só o necessário, sem poluição visual.
- **Escalas corretas**: não manipular eixos para exagerar diferenças.
- **Cores**: use contraste e significado (ex.: verde = positivo, vermelho = alerta).
- **Consistência**: mesma métrica = mesma cor em todos os gráficos.
- **Acessibilidade**: cuidado com daltonismo; use padrões além de cores.

> ⚠️ **Atenção**: “mentir com gráficos” (manipular escalas, cores ou proporções) é antiético e compromete decisões.

---

## 4) 📊 Dashboards: visão integrada

### 4.1 O que é um Dashboard?

- **Painel visual** com múltiplos gráficos e indicadores (KPIs).
- Deve ser **dinâmico**, **filtrável** e **atualizável em tempo real** (quando possível).

### 4.2 KPIs (Indicadores-chave)

- **Educação**: taxa de entrega, presença, média por disciplina.
- **Finanças**: receita, margem, inadimplência.
- **Marketing**: alcance, CTR, ROI.
- **Saúde**: tempo de espera, taxa de retorno, satisfação.
- **Vendas**: taxa de conversão, tempo médio de resposta.

### 4.3 Estrutura básica

- **Topo**: resumo (3–5 KPIs principais).
- **Meio**: gráficos detalhados (comparações, tendências).
- **Base**: filtros, tabela detalhada/exportação.

---

## 5) 🖥️ Ferramentas de Visualização

- **Planilhas (Excel/Google Sheets)**: bom para iniciantes e relatórios rápidos.
- **Power BI/Tableau**: dashboards interativos e profissionais.
- **Google Data Studio/Looker**: integração com serviços Google.
- **Python (Matplotlib/Seaborn/Plotly)**: personalização avançada e automação.
- **QGIS**: mapas e análises geográficas.

> 💡 **Sugestão**: escolha a ferramenta conforme o **público-alvo** e o **nível de detalhe** exigido.

---

## 6) ⚖️ Ética e LGPD na Visualização

- **Anonimizar dados** pessoais em relatórios públicos.
- **Consentimento**: só use dados de pessoas quando autorizado.
- **Evitar vieses**: não apresentar dados de forma a reforçar preconceitos.
- **Transparência**: indicar fonte dos dados e limitações.
- **LGPD**: respeitar direitos do titular (acesso, correção, eliminação).

---

## 7) 🧪 Estudos de Caso

### 7.1 Educação

Um colégio cria dashboard com:

- KPIs: % de entrega de tarefas, média por turma, faltas.
- Gráficos: linhas (evolução), barras (comparação entre turmas), radar (habilidades).
  Resultado: professores identificam alunos com baixo desempenho rapidamente.

### 7.2 Marketing

Uma agência monta dashboard de campanha:

- KPIs: CTR, alcance, ROI.
- Gráficos: barras empilhadas (origem dos leads), linha (evolução do CTR).
  Resultado: cliente ajusta estratégia de mídia com base em dados.

### 7.3 Saúde

Uma clínica usa BI:

- KPIs: tempo médio de espera, taxa de retorno.
- Gráficos: pizza (tipos de atendimento), dispersão (idade × frequência).
  Resultado: redução de 15% no tempo de espera.

---

## 8) ✅ Checklists

**Antes de publicar um gráfico/dashboard**:

- [ ] Título claro e objetivo.
- [ ] Escala correta e proporcional.
- [ ] Legendas legíveis.
- [ ] Cores com contraste e acessibilidade.
- [ ] Dados atualizados e confiáveis.
- [ ] Fontes citadas.
- [ ] Respeito à LGPD.

---

## 🧪 Atividades Práticas

1. **Escolha de gráfico**: dada uma tabela com dados de vendas por região, escolha 2 tipos de gráfico e justifique sua escolha.
2. **Criação de dashboard**: monte no Google Sheets/Excel um painel com pelo menos 3 gráficos e 2 KPIs.
3. **Infográfico**: desenvolva um infográfico sobre uso da tecnologia em sua área de interesse.
4. **Má prática**: crie um gráfico “enganoso” (escala manipulada, excesso de elementos) e depois corrija-o.
5. **LGPD aplicada**: simule a anonimização de uma tabela de alunos (nome → iniciais, CPF → suprimido, idade → faixa etária).

---

## 🎓 Conclusão

Visualizar dados é **contar histórias com números**. Profissionais que dominam essa habilidade conseguem transformar tabelas complexas em **decisões rápidas e embasadas**. Mais do que estética, é sobre **clareza, ética e impacto real**.
No mercado de trabalho, ser capaz de **montar dashboards, escolher gráficos adequados e respeitar a LGPD** diferencia você como **profissional de dados e de gestão**.

---

# 🧠 Fixação de Conteúdo

### ✅ 1) Dissertativas

1. Explique a importância da visualização de dados para a tomada de decisão.
2. Compare três tipos de gráficos (linha, pizza, dispersão), destacando situações ideais para uso.

---

### 🔘 2) Múltipla Escolha (uma correta)

1. Qual gráfico é mais indicado para mostrar a evolução das vendas ao longo de 12 meses?

   - [ ] Pizza
   - [ ] Linha
   - [ ] Barras empilhadas
   - [ ] Treemap

2. Um dashboard deve ter como característica principal:

   - [ ] Excesso de gráficos e cores
   - [ ] Visão integrada e clara
   - [ ] Uso apenas de tabelas
   - [ ] Falta de interatividade

3. Em visualização ética de dados, devemos:

   - [ ] Omitir valores negativos
   - [ ] Manipular escalas para convencer
   - [ ] Apresentar fontes e limitações
   - [ ] Usar apenas gráficos de pizza

---

### ☐ 3) Caixa de Seleção

Quais são boas práticas de visualização?

- [ ] Escalas proporcionais
- [ ] Cores acessíveis
- [ ] Gráficos sobrecarregados de elementos
- [ ] Pizza com 10 fatias
- [ ] Indicar fonte dos dados
- [ ] Títulos claros

---

### 🔗 4) Associação de Colunas

Associe o gráfico ao objetivo:

| Gráfico       | Objetivo                 |
| ------------- | ------------------------ |
| Linha         | Tendência temporal       |
| Barras        | Comparação de categorias |
| Dispersão     | Relação entre variáveis  |
| Pizza         | Proporção de um todo     |
| Mapa de calor | Intensidade geográfica   |

---

### ✔️ 5) Verdadeiro ou Falso

a) Dashboards devem ter KPIs visíveis e claros.
b) Gráficos de pizza são recomendados para mais de 10 categorias.
c) Escalas manipuladas podem distorcer conclusões.
d) Anonimização de dados pessoais é exigência da LGPD em relatórios públicos.

- [ ] F V V V
- [ ] V F V V
- [ ] V F F V
- [ ] F V F V

---

### 🚀 6) Desafio

Escolha uma base de dados (ex.: notas de alunos, vendas fictícias, presença em eventos) e:

- Crie 3 gráficos diferentes (comparação, tendência, proporção).
- Monte um mini-dashboard com pelo menos 2 KPIs.
- Explique quais decisões poderiam ser tomadas com base nesses dados.
- Verifique se há dados pessoais → se houver, **anonimize-os** antes da visualização.

---

## 📚 Referências Complementares

- Few, S. _Show Me the Numbers: Designing Tables and Graphs to Enlighten_.
- Knaflic, C. _Storytelling with Data_.
- 📺 [O que é Business Intelligence](https://www.youtube.com/watch?v=pzJZbP0W-bk)
- 📺 [Dashboards no Power BI](https://www.youtube.com/watch?v=ebw4JIM3PVk)
- 📖 LGPD – Lei Geral de Proteção de Dados (Lei nº 13.709/2018).
