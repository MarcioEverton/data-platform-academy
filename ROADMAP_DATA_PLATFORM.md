# DATA PLATFORM ACADEMY — ROADMAP E ESPECIFICAÇÃO EDUCACIONAL

> Documento de contexto para o projeto **Data Platform** no Claude.  
> Idioma: português brasileiro.  
> Natureza: especificação de conteúdo, currículo, experiência educacional e requisitos funcionais; **não é código-fonte**.  
> Referência curricular principal: os 14 estágios do roadmap Ensina Dev fornecidos pelo estudante. O conteúdo abaixo os desenvolve e complementa; não deve ser confundido com uma transcrição oficial do site.

## 1. Visão do produto

Criar a **Data Platform Academy**, uma plataforma pessoal de aprendizado que rode **offline no navegador após a instalação/preparação inicial**, com conteúdos didáticos originais disponíveis localmente, exercícios, avaliações, projetos e acompanhamento de progresso persistente. Abranger três eixos conectados:

1. **Engenharia de Dados — Ensina Dev:** preservar os 14 estágios, sequência e conceitos centrais fornecidos pelo estudante.
2. **Análise de Dados e BI:** fortalecer estatística, exploração de dados, visualização, Power BI, Power Query e DAX.
3. **Microsoft Power Platform:** rotas próprias de Power Fx, Power Apps, Power Automate Cloud, Power Automate Desktop, Dataverse, Copilot Studio, Power Pages, administração, governança e ALM.

Cada rota possui progresso independente. Assuntos compartilhados devem ser reaproveitados como pré-requisitos recomendados, sem obrigar o aluno a repetir conteúdos já aprovados. O aluno pode navegar livremente; a sequência ideal deve estar destacada, não rigidamente bloqueada.

### 1.1 Perfil de aprendizagem e exemplos

Começar do básico, com explicações simples antes das explicações técnicas. Usar exemplos de estoque, solicitações de materiais, movimentações, aprovações, compras, vendas, logística e indicadores gerenciais. Empregar **dados fictícios**: jamais exigir dados confidenciais de empresas. Progressivamente apresentar arquiteturas e boas práticas profissionais.

### 1.2 Princípios inegociáveis

- **Aprender fazendo:** conteúdo completo, demonstração, prática guiada e prática independente.
- **Documentação primeiro:** referências de fontes oficiais e explicações originais em português.
- **Offline real:** consultar aulas, exercícios e resultados sem conexão. Links externos são opcionais e podem não abrir sem internet.
- **Progresso confiável:** persistência local, versionamento, backup e recuperação.
- **Avaliação verificável:** respostas, justificativas, critérios e histórico de tentativas.
- **Sem aparência enganosa:** não indicar que funcionalidades simuladas executam Power Apps, serviços Cloud ou fluxos Microsoft de verdade.
- **Desenvolvimento incremental:** entregar e testar um módulo completo antes de escalar produção de conteúdo.

---

## 2. Modelo pedagógico e estrutura

Hierarquia: **Área → Rota → Módulo → Unidade → Aula → Exercício → Avaliação**.

Cada **aula** deve incluir:

1. Título, objetivos mensuráveis, nível, duração aproximada e pré-requisitos.
2. Explicação intuitiva em português e aprofundamento técnico progressivo.
3. Glossário de termos técnicos e um exemplo cotidiano.
4. Um exemplo realista de análise de dados, automação ou processo empresarial.
5. Código ou expressões revisadas (quando aplicável), com explicação por blocos.
6. Referências oficiais: título, produto, URL canônica verificada quando possível, data/versão se relevante, e nota de que o link exige conexão.
7. Exercício guiado, exercício independente e feedback de erros frequentes.
8. Resumo, perguntas de recuperação ativa e sugestão de revisão.

Cada **unidade** terá 3–10 aulas conforme a complexidade, revisão e avaliação curta de **5–10 questões**. Cada **módulo** terminará com avaliação de **20 questões**, cobrindo conceitos e aplicação. Os exercícios podem ter múltipla escolha, verdadeiro/falso, ordenação, análise de código, interpretação de resultados e tarefas práticas com critérios claros. Não confundir testes de conhecimento com comprovação de execução real em plataformas externas.

**Critério de aprovação:** nota mínima de **70/100** na avaliação final. Reprovação mantém o módulo em andamento e recomenda revisão específica. Permitir refazer, guardar todas as tentativas, maior nota e última nota. Respostas e explicações detalhadas só aparecem após a submissão. Utilizar banco de questões amplo e seleção diversificada quando houver material suficiente; não inventar variações artificiais.

**Conclusão:** aula concluída após atividades obrigatórias; unidade após aulas e avaliação correspondente; módulo após todas as unidades e aprovação final. Diferenciar porcentagem de conteúdo realizado, porcentagem de avaliações aprovadas e status final. O aluno pode revisar aulas concluídas.

**Revisão espaçada:** agendar recomendações 1, 3, 7 e 14 dias após a conclusão; armazenar registros locais e adaptar as recomendações ao desempenho. Tempo de estudo deve ser medido por períodos ativos, não apenas por uma aba aberta.

---

## 3. Rota A — Engenharia de Dados (roadmap Ensina Dev, 14 estágios)

> A numeração e os nomes são preservados conforme o roadmap fornecido; os itens a seguir servem como ementa mínima para o Claude dividir em unidades e aulas reais.

### Fase 1 — Fundamentos

#### A01. Lógica de programação
**Objetivo:** aprender a decompor problemas e descrever algoritmos.

**Unidades sugeridas:**
1. Pensamento computacional: entrada, processamento, saída, decomposição, abstração e pseudocódigo.
2. Variáveis, constantes, tipos, operadores, expressões, precedência.
3. Condicionais, operadores lógicos, tabelas-verdade e decisões.
4. Repetições, contadores, acumuladores, condições de parada.
5. Funções, parâmetros, retorno, escopo e modularidade.
6. Vetores/listas, tabelas e resolução de problemas.
7. Prática: validar quantidades, identificar estoque baixo e calcular totais.

**Projeto:** algoritmo de classificação e reposição de itens de estoque fictício.

#### A02. Python
**Objetivo:** usar Python para programar soluções e manipular dados/arquivos.

**Unidades sugeridas:**
1. Instalação e execução; interpretador, scripts, sintaxe, indentação.
2. Tipos, strings, números, conversões, operadores.
3. Condições, laços e compreensão de listas.
4. Listas, tuplas, conjuntos e dicionários.
5. Funções, módulos, pacotes, importações, escopo, type hints introdutórios.
6. Arquivos, caminhos, CSV, JSON e tratamento de exceções.
7. Ambientes virtuais, dependências, testes básicos e organização.
8. Automação simples: consolidar arquivos fictícios de movimentos de estoque.

**Projeto:** script que lê CSVs de movimentação, valida dados e gera resumo.

#### A03. SQL e bancos de dados
**Objetivo:** consultar, combinar e resumir dados com correção.

**Unidades sugeridas:**
1. Bancos relacionais, tabelas, registros, chaves e integridade.
2. SELECT, WHERE, ORDER BY, LIMIT, NULL, CASE, funções.
3. GROUP BY, HAVING, COUNT, SUM, AVG e agregações por nível.
4. INNER/LEFT/RIGHT/FULL JOIN: cardinalidade e prevenção de duplicações que alteram somas.
5. Subconsultas, CTEs e expressões reutilizáveis.
6. Funções de janela: ROW_NUMBER, RANK, LAG/LEAD, PARTITION BY.
7. Datas, calendários, séries temporais, acumulados e comparações.
8. Índices, EXPLAIN, plano de execução e otimização introdutória.
9. Exercícios de consistência de contagens, totais e granularidade.

**Projeto:** análise SQL de solicitações, saldo de estoque e movimentações.

### Fase 2 — Core

#### A04. Análise de dados com Python
**Unidades:** NumPy e arrays; pandas Series/DataFrame; leitura CSV/Excel/JSON; tipos e datas; limpeza e valores ausentes; filtros e agrupamentos; merge/join e cardinalidade; pivot/tabelas agregadas; estatística descritiva; análise exploratória; visualização com Matplotlib e Seaborn; teste e qualidade das transformações.

**Projeto:** notebook reproduzível de análise de estoque e consumo fictício.

#### A05. Modelagem de dados e Data Warehousing
**Unidades:** modelo relacional e normalização; OLTP × OLAP; data warehouse e métricas; processos de negócio e granularidade; modelo dimensional de Kimball; tabelas fato e dimensão; esquema estrela e floco de neve; dimensões de data e conformadas; Slowly Changing Dimensions (SCD); cargas históricas; armazenamento colunar em nuvem.

**Projeto:** modelar esquema estrela para solicitações, movimentações e itens.

#### A06. ETL e ELT: ingestão de dados
**Unidades:** ETL × ELT; fontes em bancos, arquivos e APIs; extração; CSV/JSON/Parquet/Avro; transformação, validação e tipagem; estratégias full e incremental; CDC conceitual; idempotência, deduplicação e upsert; reconciliação e rastreabilidade; reprocessamento e recuperação de falhas; logs e monitoramento.

**Projeto:** pipeline CSV → limpeza → banco analítico local com checkpoints.

#### A07. Orquestração de pipelines
**Unidades:** limitações do cron isolado; DAGs; arquitetura Apache Airflow; tasks/operators; agendamento e data intervals; dependências e trigger rules; retries, timeouts e idempotência; sensores; dependências entre DAGs; parametrização, observabilidade e operação.

**Projeto:** desenho e implementação demonstrativa de DAG de ingestão com dependências e tratamento de falhas (execução real do Airflow é opcional e não deve ser simulada como real).

### Fase 3 — Avançado

#### A08. Processamento distribuído com Spark
**Unidades:** por que distribuir; driver/executors/cluster; partições; lazy evaluation; RDDs × DataFrames; PySpark e Spark SQL; transformations/actions; joins e shuffle; particionamento; cache; Catalyst e AQE; Spark UI; testes, tuning e custos.

**Projeto:** pipeline PySpark com dados sintéticos em escala, com alternativa conceitual para navegador offline.

#### A09. Data Lake e Lakehouse
**Unidades:** warehouse × lake; object storage; zonas raw/curated; particionamento; limites do lake cru; ACID e transações; upsert e time travel; Delta Lake; Apache Iceberg; Apache Hudi; arquitetura medalhão bronze/silver/gold; manutenção, evolução de esquema e qualidade das tabelas.

**Projeto:** desenhar lakehouse de movimentações com camadas bronze, silver e gold.

#### A10. Streaming e dados em tempo real
**Unidades:** batch × streaming; eventos e mensageria; Kafka tópicos/partições/offsets; producers e consumers; grupos de consumo; at-least-once e exactly-once como garantias condicionais; duplicação e idempotência; event time vs processing time; watermarks e janelas; Structured Streaming; observabilidade.

**Projeto:** arquitetura de ingestão de eventos de pedidos e atualização de métricas.

#### A11. Modern Data Stack e Analytics Engineering
**Unidades:** arquitetura ELT moderna; dbt projects; modelos e `ref()`; lineage; materializações view/table/incremental; sources, testes e documentação; Jinja/macros/packages; snapshots; semantic layer; métricas; CI/CD e governança de mudanças.

**Projeto:** camada de transformação com modelos, testes e documentação de métricas.

### Fase 4 — Deploy e governança

#### A12. Containers e empacotamento de pipelines
**Unidades:** containers vs VMs; Docker e imagens; Dockerfile; camadas e cache; volumes e redes; Docker Compose; variáveis e segredos; imagens enxutas; vulnerabilidades; reprodutibilidade e ambientes.

**Projeto:** empacotar pipeline de ingestão com dependências e persistência.

#### A13. CI/CD e cloud para dados
**Unidades:** Git, branching e revisão; testes automatizados; GitHub Actions e workflows; builds; publicação de imagens; deploy contínuo; conceitos de computação e armazenamento cloud; credenciais; HTTPS; logs, métricas e rastreamento; noções de custo e operação.

**Projeto:** pipeline de CI para testes de transformação, com deploy documentado.

#### A14. Qualidade, governança e confiabilidade de dados
**Unidades:** dimensões de qualidade (completude, validade, consistência etc.); contratos de dados; testes e alertas; observabilidade; lineage e catálogos; ownership; classificação e proteção de dados; LGPD; controle de acesso; retenção; FinOps; incidentes e recuperação; capstone integrador.

**Capstone:** projetar plataforma de dados ponta a ponta, com ingestão, transformação, modelo analítico, controles de qualidade, documentação, monitoramento e dashboard.

---

## 4. Rota B — Análise de Dados, Estatística e Business Intelligence

Esta rota é **independente e complementar** à rota de 14 estágios. Compartilha SQL, Python e modelagem quando úteis.

| Código | Módulo | Unidades mínimas | Projeto/avaliação |
|---|---|---|---|
| B01 | Fundamentos de análise de dados | Perguntas de negócio; KPIs; granularidade; fontes; qualidade; processo analítico | Planejar análise de desempenho operacional |
| B02 | Estatística aplicada | Medidas de tendência e dispersão; distribuições; amostragem; correlação vs causalidade; hipóteses; intervalos de confiança; vieses | Interpretar variação de tempos de atendimento |
| B03 | Excel para análise | Tabelas; fórmulas; procura; Tabelas Dinâmicas; limpeza; gráficos; boas práticas | Relatório de estoque fictício |
| B04 | SQL analítico | Agregação; joins; janelas; coortes; séries temporais; qualidade | Consultas analíticas de vendas |
| B05 | Python e análise exploratória | pandas; NumPy; limpeza; exploração; gráficos; conclusões | EDA de solicitações e movimentações |
| B06 | Power Query | Fontes; tipos; etapas; M básico; combinar/anexar; parâmetros; atualização | Transformar arquivos de estoque |
| B07 | Modelagem para BI | Fato/dimensão; cardinalidade; filtros; esquema estrela; calendário; granularidade | Modelo de vendas e estoque |
| B08 | DAX fundamental | Contexto de linha e filtro; medidas vs colunas; CALCULATE; SUMX; FILTER; DIVIDE; variáveis | Medidas de estoque e atendimento |
| B09 | DAX avançado | Modificadores de filtro; inteligência temporal; tabelas virtuais; desempenho e depuração | Indicadores de tendência e comparações |
| B10 | Visualização e storytelling | Escolha de visuais; acessibilidade; indicadores; hierarquia; narrativa; armadilhas | Dashboard executivo |
| B11 | Power BI Service e segurança | Publicação; workspaces; atualização; gateway; permissões; RLS; governança | Plano de publicação segura |
| B12 | Projeto de portfólio de BI | Briefing; ingestão; modelo; medidas; UX; validação com usuário; documentação | Dashboard completo com dados sintéticos |

**Observação:** exercícios de DAX e Power BI offline poderão ser questões, leitura/depuração de fórmulas e atividades simuladas; não afirmar execução real do motor DAX ou do Power BI dentro do navegador sem motor verificado.

---

## 5. Rota C — Microsoft Power Platform

### C01. Power Fx — rota prioritária e aprofundada

**Objetivo:** dominar a linguagem de fórmulas e os padrões de desenvolvimento utilizados principalmente em Canvas Apps, com compreensão de limitações, tipos de fórmulas e desempenho.

**Unidades obrigatórias:**
1. Introdução à Power Fx: linguagem declarativa, fórmulas, comportamento, recálculo e propriedades de controle.
2. Sintaxe e ambiente: expressões, valores, referências a controles, identificadores, tipos, operadores e separadores regionais (em pt-BR, `;` e `;;` conforme contexto e editor).
3. Texto e números: `Text`, `Value`, `Concatenate`, `Len`, `Left`, `Mid`, `Right`, `Trim`, `Substitute`, `Round` e formatação regional.
4. Lógica e condições: `If`, `Switch`, `And`, `Or`, `Not`, `IsBlank`, `IsEmpty`, `Coalesce` e validação.
5. Datas e horários: `Today`, `Now`, `DateAdd`, `DateDiff`, `DateValue`, localidade e fusos.
6. Controles e eventos: `OnSelect`, `OnChange`, `Items`, `Default`, `Visible`, `DisplayMode`, `Notify`, `Reset`, `Navigate`.
7. Variáveis e estado: `Set`, `UpdateContext`, `With`; variáveis globais, de contexto e fórmulas nomeadas quando disponíveis.
8. Tabelas e registros: tipos de registro/tabela; `Table`, `ShowColumns`, `AddColumns`, `DropColumns`, `RenameColumns` e campos complexos.
9. Coleções: `Collect`, `Clear`, `ClearCollect`, `Remove`, `RemoveIf`, `UpdateIf`, uso adequado e limites.
10. Pesquisa e filtros: `Filter`, `Search`, `LookUp`, `StartsWith`, `Sort`, `SortByColumns`, escolha de fontes e delegação.
11. Agregações e iteração: `CountRows`, `CountIf`, `Sum`, `Average`, `ForAll`, registros aninhados, `ThisRecord`, `As` e `Sequence`.
12. Persistência e CRUD: `Patch`, `Defaults`, `SubmitForm`, `EditForm`, `NewForm`, `Remove`, erros e concorrência.
13. Tratamento de erros: `IfError`, `Errors`, mensagens, validação de entrada, integridade e permissões.
14. Formulários e componentes: galerias, combos, datacards, validação por item, estado e comportamento responsivo.
15. Delegação e desempenho: limites de linhas, aviso de delegação, consultas eficientes, evitar N+1, coleções vs fontes e monitoramento.
16. Integração: SharePoint, Dataverse, Power Automate; conectores, parâmetros e respostas.
17. Segurança, acessibilidade, nomenclatura, documentação e testes.
18. Laboratório final: app de requisições de materiais com estoque fictício, aprovação, validações e histórico de status.

**Exercícios de fórmulas:** prever resultados, corrigir erros, explicar delegação, selecionar funções, completar expressões e elaborar fórmulas para cenários. Para fórmulas Power Fx, apresentar o contexto de propriedade e a localidade sintática; não misturar sintaxe inglesa com separadores pt-BR sem explicação. Exercícios offline podem validar padrões e respostas pré-calculadas, mas **não representam um interpretador Power Fx completo**.

### C02. Power Apps — Canvas Apps

**Unidades:** experiência do Studio; telas e navegação; propriedades e controles; layouts e responsividade; galerias e formulários; Power Fx aplicado; conectores; SharePoint; Dataverse; CRUD; componentes; filtros; validações; estados de carregamento; permissões; acessibilidade; testes; publicação e compartilhamento; manutenção e performance.

**Projeto:** aplicativo fictício de solicitações de materiais, com seleção de estoque, carrinho, centro de custo, conta e aprovação.

### C03. Power Automate Cloud

**Unidades:** gatilhos manuais, automatizados e agendados; conectores; ações; variáveis; condições; loops e concorrência; expressões e operações de dados; JSON e Parse JSON; SharePoint/Excel/Outlook/Teams; aprovações; escopos, retries, run after e tratamento de erros; paginação, limites, throttling e otimização; idempotência; monitoramento; soluções e ALM.

**Projeto:** automação fictícia de aprovação e sincronização incremental de dados. Destacar quando conectores exigem licenças específicas e validar informação atual nas fontes Microsoft.

### C04. Power Automate Desktop — RPA

**Unidades:** arquitetura de RPA; variáveis e tipos; ações e subfluxos; Excel; arquivos e pastas; tratamento CSV; UI automation; seletores; aplicações desktop; web automation; condições e loops; tratamento de exceções; logs; execução assistida/não assistida e pré-requisitos; integração com fluxos cloud; VM e segurança; desempenho e manutenção.

**Projeto:** ler relatório de estoque fictício, validar e tratar dados, comparar versões, registrar diferenças e gerar arquivo de saída — com execução real apenas no ambiente Windows apropriado.

### C05. Dataverse

**Unidades:** conceitos; ambientes; tabelas padrão/personalizadas; colunas e tipos; relacionamentos; choices; regras de negócios; formulários e views; segurança por papéis; equipes; permissões; auditoria; soluções; integrações e boas práticas de modelagem.

**Projeto:** modelo de dados para solicitações, aprovações, itens e movimentações.

### C06. Copilot Studio

**Unidades:** criação de agentes; tópicos e instruções; fontes de conhecimento; ações e ferramentas; integrações Power Automate; variáveis; testes; segurança, governança e monitoramento; limites e validação de respostas.

**Projeto:** agente de suporte a dúvidas de estoque com base fictícia e regras de encaminhamento.

### C07. Power Pages

**Unidades:** arquitetura e sites; templates; páginas e componentes; formulários e listas; Dataverse; identidade e autenticação; web roles e table permissions; acessibilidade; segurança e publicação.

**Projeto:** portal fictício para acompanhar solicitações, com desenho de permissões.

### C08. Power BI e Power Query — rota Microsoft detalhada

**Unidades:** importação e DirectQuery; Power Query e M; modelagem e esquema estrela; DAX; filtros e contextos; visuais; performance; atualização; gateways; workspaces; segurança/RLS; compartilhamento e licenças; governança.

**Projeto:** dashboard de estoque, rupturas e tempo de atendimento com dados fictícios. Conectar esta rota aos módulos B06–B11 sem duplicar progresso.

### C09. SharePoint e Microsoft Lists para soluções Power Platform

**Unidades:** sites e listas; tipos de campo; identificadores; permissões; views; índices; limites de consulta; anexos; versionamento; integração com Power Apps/Automate; desempenho, governança e cuidados com volumes grandes.

**Projeto:** desenho de armazenamento para catálogo de materiais e solicitações.

### C10. Administração, governança e ALM

**Unidades:** ambientes; estratégia de desenvolvimento/teste/produção; roles e DLP; conectores padrão e premium; licenciamento (consultar documentação atual); soluções gerenciadas e não gerenciadas; connection references; environment variables; pipelines; CoE; telemetria; auditoria; políticas de segurança e continuidade.

**Projeto:** plano de implantação e governança de uma solução corporativa.

### C11. Integrações Microsoft 365 e Azure para Power Platform

**Unidades:** Excel e OneDrive; Outlook; Teams; Microsoft Forms; SharePoint; conectores HTTP (restrições e licenciamento); APIs REST como conhecimento opcional; conceitos de Azure Functions, Azure Storage, Azure SQL e identidade; integração responsável com Power Platform.

**Projeto:** arquitetura comparada de integração de dados; não presumir disponibilidade de licenças premium.

### C12. Projetos integrados Microsoft Power Platform

**Unidades/projetos:** (a) requisição e aprovação de materiais; (b) atualização diária de dados com validação; (c) notificações e trilhas de auditoria; (d) dashboard operacional; (e) agente de suporte; (f) solução empacotada e governada. Em cada projeto: escopo, critérios de aceitação, dados sintéticos, passo a passo, avaliação e limitações offline.

---

## 6. Catálogo transversal de documentação oficial

> As URLs abaixo são **pontos de entrada indicativos**. O desenvolvedor deve verificar a URL específica da aula antes de registrá-la como referência validada, pois páginas e versões podem mudar. Toda referência deve informar seu status: `verificada`, `a_verificar` ou `indisponivel`.

| Tema | Fonte oficial de referência |
|---|---|
| Python | https://docs.python.org/3/ |
| PostgreSQL | https://www.postgresql.org/docs/ |
| SQLite | https://www.sqlite.org/docs.html |
| NumPy | https://numpy.org/doc/ |
| pandas | https://pandas.pydata.org/docs/ |
| Matplotlib | https://matplotlib.org/stable/ |
| Apache Airflow | https://airflow.apache.org/docs/ |
| Apache Spark | https://spark.apache.org/docs/latest/ |
| Apache Kafka | https://kafka.apache.org/documentation/ |
| Apache Iceberg | https://iceberg.apache.org/docs/latest/ |
| Delta Lake | https://docs.delta.io/ |
| dbt | https://docs.getdbt.com/ |
| Docker | https://docs.docker.com/ |
| GitHub Actions | https://docs.github.com/en/actions |
| Power Fx | https://learn.microsoft.com/en-us/power-platform/power-fx/ |
| Power Apps | https://learn.microsoft.com/en-us/power-apps/ |
| Power Automate | https://learn.microsoft.com/en-us/power-automate/ |
| Power Automate Desktop | https://learn.microsoft.com/en-us/power-automate/desktop-flows/ |
| Power BI | https://learn.microsoft.com/en-us/power-bi/ |
| Power Query | https://learn.microsoft.com/en-us/power-query/ |
| Dataverse | https://learn.microsoft.com/en-us/power-apps/maker/data-platform/ |
| Copilot Studio | https://learn.microsoft.com/en-us/microsoft-copilot-studio/ |
| Power Pages | https://learn.microsoft.com/en-us/power-pages/ |
| Power Platform administração | https://learn.microsoft.com/en-us/power-platform/admin/ |
| Microsoft Learn | https://learn.microsoft.com/en-us/training/ |

**Regra editorial:** aulas devem conter conteúdo **autoral e suficiente para estudar sem internet**, com referências externas complementares; não replicar integralmente documentação protegida por direitos autorais. Para ferramentas cujo comportamento varia por versão/licença, inserir observação sobre validade temporal.

---

## 7. Funcionalidades exigidas da plataforma

### 7.1 Painel inicial

Mostrar: saudação neutra, botão **Continuar estudando**, progresso geral e por rota, módulos concluídos, últimas avaliações, revisões pendentes, tempo ativo de estudo, calendário de atividade, metas, conquistas e próximos conteúdos recomendados.

### 7.2 Roadmaps e navegação

- Lista e visualização em etapas interligadas; categorias Fundamentos/Core/Avançado/Deploy para Ensina Dev e agrupamentos adequados nas demais rotas.
- Módulos acessíveis para consulta mesmo sem concluir pré-requisitos.
- Estados `nao_iniciado`, `em_andamento`, `aguardando_avaliacao`, `concluido`.
- Filtros por assunto, tecnologia, nível e status; pesquisa global offline.
- Favoritos, marcadores, anotações e revisão por aula.

### 7.3 Progresso, notas e avaliações

- Persistência de aulas/unidades/módulos, tentativas, gabaritos submetidos, resultados e revisões.
- Escala de nota 0–100, aprovação >=70, histórico e feedback por objetivo de aprendizagem.
- Diferenciar acerto de quiz de execução prática validada.
- Possibilidade de exportar/importar dados com validação e migração de versões.

### 7.4 Laboratórios offline

- **SQL:** preferir SQLite WASM empacotado localmente, com tabelas de exemplo; analisar resultados das consultas em vez de comparar texto literal. Se inviável, explicar limitação.
- **Python:** editor com destaque de sintaxe; executar apenas quando houver runtime real disponível offline (por exemplo, Pyodide distribuído junto ao build) e isolamento adequado. Nunca apresentar saída falsa.
- **Power Fx:** atividades de interpretação/correção de fórmulas e checagens de respostas; não afirmar possuir motor completo de Power Fx sem comprovação.
- **Power BI/Power Automate/Dataverse etc.:** exercícios teóricos, interativos e cenários locais; sinalizar claramente que execução real requer aplicações, contas ou serviços apropriados.
- Conjuntos sintéticos locais em CSV/JSON, com esquema e dicionário de dados.

### 7.5 Armazenamento e offline

- Preferir **IndexedDB** para progresso, respostas, anotações e preferências.
- Conteúdo didático estático distribuído com a aplicação e, quando necessário, cache local versionado.
- Exportação JSON com `schemaVersion`, `exportedAt` e dados validados; importação transacional ou com rollback, nunca apagar progresso por falha de leitura.
- Evitar qualquer dependência de CDN, API externa, imagem, fonte ou conteúdo remoto para navegação e aprendizado essenciais.
- Oferecer build para execução local; se PWA/Service Worker, observar que geralmente exigem contexto seguro (HTTPS/localhost). Um build Vite/React pode exigir servidor HTTP local, **não prometer** que abrir `index.html` diretamente via `file://` funcionará.
- Explicar riscos de limpar dados do navegador e incentivar backup periódico.

### 7.6 Acessibilidade e design

- Interface em português brasileiro, desktop-first com responsividade para mobile.
- Tema claro/escuro, teclado, foco visível, contraste adequado, rótulos acessíveis, estados vazios e mensagens claras.
- Referências visuais: Microsoft Learn (documentação), roadmap.sh (trilhas), Coursera (organização) e Duolingo (motivação sem excesso de gamificação).
- Menu: Dashboard; Rotas; Continuar; Biblioteca; Laboratórios; Avaliações; Revisões; Estatísticas; Conquistas; Configurações.

---

## 8. Modelo conceitual de dados

Entidades mínimas:

- `LearningPath`: `id`, `title`, `description`, `area`, `moduleIds`, `version`.
- `Module`: `id`, `pathId`, `title`, `level`, `summary`, `unitIds`, `prerequisiteIds`.
- `Unit`: `id`, `moduleId`, `title`, `lessonIds`, `quizId`.
- `Lesson`: `id`, `unitId`, `title`, `objectives`, `contentBlocks`, `references`, `exerciseIds`, `estimatedMinutes`.
- `Exercise`: `id`, `lessonId`, `type`, `prompt`, `validation`, `feedback`.
- `Assessment`: `id`, `scope`, `questionIds`, `passingScore`, `version`.
- `Question`: `id`, `type`, `prompt`, `choices`, `answerSpec`, `explanation`, `objectiveTags`, `difficulty`.
- `LessonProgress`: `lessonId`, `status`, `completedAt`, `lastVisitedAt`, `exerciseResults`.
- `AssessmentAttempt`: `assessmentId`, `startedAt`, `submittedAt`, `answers`, `score`, `passed`.
- `StudySession`: `startedAt`, `endedAt`, `activeSeconds`, `lessonId`.
- `ReviewSchedule`: `lessonId`, `nextReviewAt`, `intervalDays`, `lastResult`.
- `UserNote`, `Bookmark`, `Preference`, `BackupMetadata`.

Usar **IDs estáveis** independentes de nomes e ordem de apresentação. Definir regras de migração para mudanças de conteúdo e respeitar progresso já registrado. Evitar que uma aula compartilhada seja marcada incorretamente como duas conclusões distintas; distinguir conteúdo canônico de sua presença em diferentes rotas.

---

## 9. Projetos integradores e dados fictícios

Datasets locais sugeridos: `produtos.csv`, `estoque.csv`, `movimentacoes.csv`, `solicitacoes.csv`, `itens_solicitacao.csv`, `aprovadores.csv`, `fornecedores.csv`, `vendas.csv`, `clientes.csv`, `calendario.csv`.

Chaves e relações coerentes: `ProdutoId`, `SolicitacaoId`, `ItemSolicitacaoId`, `FornecedorId`, `DataId` etc. Documentar granularidade e significado dos campos. Inserir casos realistas de dados ausentes, duplicidades controladas, datas, unidades e problemas de qualidade para ensinar diagnóstico. Não utilizar arquivos de empresas reais.

Projetos em níveis:

1. **Iniciante:** classificar produtos, validar quantidade e produzir resumos.
2. **Intermediário:** analisar pedidos e movimentações com SQL/Python.
3. **Modelagem:** fato de movimentação + dimensões produto, local, tempo.
4. **Automação:** fluxo de aprovação e atualização com tratamento de erros.
5. **BI:** dashboard com KPIs, modelos e medidas documentadas.
6. **Avançado:** pipeline com incrementais, testes, orquestração e modelo Lakehouse.
7. **Capstone:** sistema fictício ponta a ponta com governança, observabilidade e explicação arquitetural.

Cada projeto inclui contexto, pergunta de negócio, requisitos, dados, entregas, rubrica, critérios de aceite, dicas progressivas e correção/autoavaliação.

---

## 10. Plano de implementação incremental para Claude

**Entrega 1 — MVP verificável:** arquitetura, navegação, catálogo de todas as rotas, módulo A01 completo com aulas reais e avaliação, progresso IndexedDB, continuidade, backup JSON, modo offline validado. Trilha C01 Power Fx cadastrada com unidades e algumas lições completas para testar coexistência das rotas; não marcar resto como concluído.

**Entrega 2 — Base pedagógica:** revisão espaçada, estatísticas corretas, anotações, pesquisa, banco de questões e exercícios mais ricos.

**Entrega 3 — Laboratórios:** SQL real offline e Python real offline se viável; testes de execução e isolamento.

**Entrega 4 — Conteúdo de Fundamentos e Power Fx:** completar A02 e A03, aprofundar C01; validação de referências.

**Entrega 5 — Demais rotas:** ampliar progressivamente A04–A14, B01–B12 e C02–C12, mantendo padrão pedagógico e revisão editorial.

**Entrega 6 — Qualidade:** acessibilidade, desempenho, testes automatizados, migrações, documentação de instalação e distribuição.

### Critérios de aceitação do MVP

1. Abrir plataforma local e acessar dashboard/roadmaps sem internet.
2. Entrar na rota A, começar A01, ler aula real e completar atividade.
3. Fechar e reabrir; manter progresso e última aula.
4. Responder quiz, receber feedback e registrar resultado.
5. Fazer avaliação do módulo; aprovar com >=70 e reprovar abaixo disso.
6. Abrir C01 Power Fx sem misturar seu progresso com a rota A.
7. Exportar backup JSON; importar em estado limpo e recuperar dados.
8. Navegar sem chamadas de rede para recursos essenciais.
9. Não haver botões decorativos ou dados de progresso fictícios apresentados como reais.
10. Informar claramente funcionalidades efetivamente testadas e limitações pendentes.

---

## 11. Instrução de uso deste documento

Este arquivo deve ser adicionado em **Contexto → Adicionar** do projeto Claude, enquanto as **Instruções** do projeto registram regras gerais permanentes de comportamento. Na conversa inicial, pedir a **Entrega 1** e solicitar implementação incremental com arquivos reais e testes. Caso a ferramenta não possa editar arquivos diretamente, ela deve fornecer estrutura, código e instruções verificáveis para o ambiente Windows.

**Ordem de prioridades:** (1) offline e persistência real; (2) aprendizagem com conteúdo verdadeiro; (3) avaliações úteis; (4) experiência de uso; (5) expansão das trilhas; (6) recursos avançados.
