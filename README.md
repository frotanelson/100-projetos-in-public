# 100 Projetos com IA — Build in Public

102 projetos construídos com [Claude Code](https://claude.com/claude-code), documentados em público do primeiro commit ao ship.

Este repositório é a **vitrine** da série: o roadmap completo, o guia de como a série é feita e os templates. O código de cada projeto vive em um repositório próprio, publicado quando o projeto é entregue.

## Fonte da lista

A lista de projetos vem do artigo da Orchids: [100+ Projects to Vibe Code with Claude Code](https://www.orchids.app/blog/what-is-claude-code-and-100-projects-to-vibe-code-with-claude-code). Os nomes e descrições seguem a lista original; o planejamento, a ordem e a execução são desta série.

## Como acompanhar

- Dê **watch/star** neste repositório: cada projeto entregue atualiza a tabela abaixo com o link do repo.
- Siga [@frotanelson](https://github.com/frotanelson) no GitHub.
- Cada entrega vem com um post (template em [BUILD_IN_PUBLIC.md](BUILD_IN_PUBLIC.md)).

## Como cada projeto é publicado

1. O projeto é planejado (PRD + plano faseado) e construído em um repositório de trabalho privado.
2. Só quando está **entregue** (Definition of Done completo, testes e revisão de segurança ok) ele ganha um **repositório público próprio**: `frotanelson/NNN-slug`.
3. A tabela abaixo é atualizada: status vira ✅ e a coluna **Repo** recebe o link.
4. O post da entrega é publicado.

Projetos ⬜ ou 🔨 não têm repositório público ainda: a coluna Repo fica com "—".

## Stack base

Trilha principal: **Python + dbt + Postgres + desenvolvimento com IA** (Claude Code como par). Cada projeto indica sua stack na tabela. Templates de PRD e PLANO em [_templates/](_templates/).

## Roadmap

**1 / 102 entregues** · legenda: ⬜ não iniciado · 🔨 em andamento · ✅ entregue

### 🟢 Iniciante (001–020) · 1-2 sessões cada

| # | Projeto | Stack | Status | Repo |
|---|---|---|---|---|
| 001 | **To-Do List App** — Gerenciador de tarefas web com adicionar, editar e excluir. | Python Web (Flask + HTMX) | ✅ | [001-todo-list-app](https://github.com/frotanelson/001-todo-list-app) |
| 002 | **Markdown Note Generator** — Converte prompts em notas markdown formatadas com headers, listas e links. | Python CLI | ⬜ | — |
| 003 | **Password Generator Tool** — Gerador de senhas seguras com tamanho e conjuntos de caracteres customizáveis. | Python CLI | ⬜ | — |
| 004 | **Weather CLI Tool** — Busca dados de clima em API pública e exibe formatado no terminal. | Python CLI | ⬜ | — |
| 005 | **Simple Calculator Web App** — Calculadora de navegador com operações matemáticas básicas. | Python Web (Flask + HTMX) | ⬜ | — |
| 006 | **Personal Expense Tracker** — Registra despesas diárias e organiza automaticamente por categoria. | Python + dbt + Postgres | ⬜ | — |
| 007 | **Random Quote Generator** — Sorteia citações de um arquivo JSON e exibe numa página web. | Python Web (Flask + HTMX) | ⬜ | — |
| 008 | **URL Shortener** — Encurtador de links com mapeamentos em banco local. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 009 | **Countdown Timer** — Timer com iniciar, pausar e resetar. | Python Web (Flask + HTMX) | ⬜ | — |
| 010 | **Color Palette Generator** — Gera esquemas de cores aleatórios para projetos de design. | Python Web (Flask + HTMX) | ⬜ | — |
| 011 | **Tip Calculator** — Calcula gorjetas e divide contas entre várias pessoas. | Python Web (Flask + HTMX) | ⬜ | — |
| 012 | **BMI Calculator** — Calcula índice de massa corporal a partir de altura e peso. | Python Web (Flask + HTMX) | ⬜ | — |
| 013 | **Stopwatch App** — Cronômetro simples com registro de voltas (laps). | Python Web (Flask + HTMX) | ⬜ | — |
| 014 | **Currency Converter** — Converte moedas usando API pública de câmbio. | Python CLI | ⬜ | — |
| 015 | **Flashcard Study Tool** — App de flashcards para prática de memorização. | Python Web (Flask + HTMX) | ⬜ | — |
| 016 | **Dice Rolling Simulator** — Simula rolagem de múltiplos dados com lados customizáveis. | Python CLI | ⬜ | — |
| 017 | **Rock Paper Scissors Game** — Jogo de pedra, papel e tesoura contra o computador no navegador. | Python Web (Flask + HTMX) | ⬜ | — |
| 018 | **Pomodoro Timer** — Timer de produtividade com intervalos de trabalho e pausa. | Python Web (Flask + HTMX) | ⬜ | — |
| 019 | **Random Name Picker** — Recebe uma lista de nomes e sorteia um aleatoriamente. | Python Web (Flask + HTMX) | ⬜ | — |
| 020 | **Simple Blog Template** — Blog estático gerado a partir de posts em markdown. | Python CLI | ⬜ | — |

### 🤖 Apps com IA (021–040) · 2-4 sessões cada

| # | Projeto | Stack | Status | Repo |
|---|---|---|---|---|
| 021 | **AI Blog Idea Generator** — Digite um tema e receba várias ideias de post com outlines. | Python + Claude API (Streamlit) | ⬜ | — |
| 022 | **Customer Support Chatbot** — Chatbot que responde perguntas comuns usando IA. | FastAPI + Claude API + Postgres | ⬜ | — |
| 023 | **Article Summarization Tool** — Cole artigos longos e receba resumos curtos. | Python + Claude API (Streamlit) | ⬜ | — |
| 024 | **Meeting Notes Generator** — Recebe transcrições de reuniões e cria action items automaticamente. | Python + Claude API (Streamlit) | ⬜ | — |
| 025 | **AI Email Draft Assistant** — Insira o contexto e receba rascunhos profissionais de e-mail. | Python + Claude API (Streamlit) | ⬜ | — |
| 026 | **Content Rewriter** — Transforma conteúdo existente em diferentes tons e formatos. | Python + Claude API (Streamlit) | ⬜ | — |
| 027 | **Social Media Caption Generator** — Escreve legendas envolventes para Instagram, X ou LinkedIn. | Python + Claude API (Streamlit) | ⬜ | — |
| 028 | **Product Description Writer** — Cria descrições de produto persuasivas a partir de listas de features. | Python + Claude API (Streamlit) | ⬜ | — |
| 029 | **Resume Bullet Point Generator** — Transforma responsabilidades de trabalho em bullets focados em conquistas. | Python + Claude API (Streamlit) | ⬜ | — |
| 030 | **AI Code Explainer** — Cole trechos de código e receba explicações em linguagem simples. | Python + Claude API (Streamlit) | ⬜ | — |
| 031 | **Sentiment Analysis Tool** — Analisa texto para determinar tom emocional e sentimento. | FastAPI + Claude API + Postgres | ⬜ | — |
| 032 | **Keyword Extractor** — Extrai palavras-chave importantes de artigos ou documentos. | Python + Claude API (Streamlit) | ⬜ | — |
| 033 | **AI Story Generator** — Cria histórias curtas baseadas em prompts e gêneros do usuário. | Python + Claude API (Streamlit) | ⬜ | — |
| 034 | **Language Translation Assistant** — Traduz texto entre idiomas com consciência de contexto. | Python + Claude API (Streamlit) | ⬜ | — |
| 035 | **AI Interview Question Generator** — Cria perguntas de entrevista sob medida para papéis específicos. | Python + Claude API (Streamlit) | ⬜ | — |
| 036 | **Personalized Learning Path Creator** — Gera planos de estudo baseados em objetivos de aprendizado. | Python + Claude API (Streamlit) | ⬜ | — |
| 037 | **AI Recipe Suggestion Tool** — Digite os ingredientes e receba ideias de receitas. | Python + Claude API (Streamlit) | ⬜ | — |
| 038 | **Writing Style Analyzer** — Analisa amostras de escrita e sugere melhorias. | Python + Claude API (Streamlit) | ⬜ | — |
| 039 | **AI Brainstorming Partner** — Gera ideias criativas para projetos ou conceitos de negócio. | Python + Claude API (Streamlit) | ⬜ | — |
| 040 | **Automated FAQ Generator** — Revisa documentação e cria perguntas frequentes automaticamente. | Python + Claude API (Streamlit) | ⬜ | — |

### 🛠️ Ferramentas Dev (041–060) · 2-4 sessões cada

| # | Projeto | Stack | Status | Repo |
|---|---|---|---|---|
| 041 | **API Testing CLI Tool** — Testa endpoints REST e exibe respostas formatadas no terminal. | Python CLI | ⬜ | — |
| 042 | **Code Snippet Manager** — Armazena e organiza snippets reutilizáveis com tags. | Python CLI | ⬜ | — |
| 043 | **Git Commit Message Generator** — Analisa mudanças staged e sugere mensagens de commit significativas. | Python CLI | ⬜ | — |
| 044 | **Markdown Documentation Generator** — Converte comentários de código em documentação estruturada. | Python CLI | ⬜ | — |
| 045 | **JSON Formatter and Validator** — Limpa JSON bagunçado e valida sua estrutura. | Python CLI | ⬜ | — |
| 046 | **Environment Variable Manager** — Armazena e gerencia variáveis de ambiente entre projetos com segurança. | Python CLI | ⬜ | — |
| 047 | **Dependency Update Checker** — Varre package.json ou requirements.txt para identificar dependências desatualizadas. | Python CLI | ⬜ | — |
| 048 | **Regex Pattern Tester** — Testa expressões regulares contra texto de exemplo com destaque de matches. | Python Web (Flask + HTMX) | ⬜ | — |
| 049 | **SQL Query Builder** — Cria queries SQL a partir de descrições em linguagem natural. | FastAPI + Claude API + Postgres | ⬜ | — |
| 050 | **Log File Analyzer** — Lê logs de aplicação para identificar erros e padrões. | Python + dbt + Postgres | ⬜ | — |
| 051 | **API Documentation Generator** — Produz documentação interativa de API a partir de definições de endpoints. | Python CLI | ⬜ | — |
| 052 | **Database Schema Visualizer** — Gera diagramas visuais a partir de schemas de banco. | Python CLI | ⬜ | — |
| 053 | **Code Diff Viewer** — Compara dois arquivos de código e destaca diferenças. | Python Web (Flask + HTMX) | ⬜ | — |
| 054 | **Port Scanner Tool** — Verifica quais portas estão abertas em um IP. | Python CLI | ⬜ | — |
| 055 | **Localhost Tunnel Manager** — Expõe servidores locais de desenvolvimento para a internet para testes. | Python CLI | ⬜ | — |
| 056 | **Build Time Tracker** — Monitora e registra tempos de build entre projetos. | Python + dbt + Postgres | ⬜ | — |
| 057 | **Git Branch Cleanup Tool** — Identifica e deleta branches mergeadas ou antigas. | Python CLI | ⬜ | — |
| 058 | **Package Size Analyzer** — Analisa tamanhos de bundle e identifica dependências grandes. | Python CLI | ⬜ | — |
| 059 | **Error Stack Trace Formatter** — Torna mensagens de erro mais fáceis de ler e agir. | Python CLI | ⬜ | — |
| 060 | **SSH Key Manager** — Gera e organiza chaves SSH para diferentes servidores. | Python CLI | ⬜ | — |

### 🚀 SaaS / Startup (061–080) · 4-8 sessões cada

| # | Projeto | Stack | Status | Repo |
|---|---|---|---|---|
| 061 | **Simple CRM Dashboard** — Acompanha interações com clientes, negócios e tarefas de follow-up. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 062 | **Content Calendar Generator** — Planeja e agenda conteúdo em múltiplas plataformas. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 063 | **Invoice Generator Web App** — Cria faturas profissionais com cálculos automáticos. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 064 | **Project Management Tool** — Organiza tarefas, prazos e atribuições de equipe. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 065 | **Customer Feedback Tracker** — Coleta e categoriza feedback de usuários de múltiplas fontes. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 066 | **Subscription Management Dashboard** — Acompanha assinaturas recorrentes e gastos. | Python + dbt + Postgres | ⬜ | — |
| 067 | **Lead Scoring System** — Ranqueia clientes potenciais por métricas de engajamento. | Python + dbt + Postgres | ⬜ | — |
| 068 | **Email Campaign Builder** — Desenha e envia e-mails de marketing com templates. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 069 | **Affiliate Link Manager** — Organiza e acompanha links de afiliados e comissões. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 070 | **Waitlist Landing Page** — Coleta e-mails para lançamentos de produtos. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 071 | **Survey Builder Tool** — Cria pesquisas customizadas e analisa respostas. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 072 | **Time Tracking App** — Registra horas faturáveis e gera relatórios para clientes. | Python + dbt + Postgres | ⬜ | — |
| 073 | **Inventory Management System** — Acompanha níveis de estoque e pontos de reposição. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 074 | **Booking and Appointment Scheduler** — Permite que clientes reservem horários online. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 075 | **Referral Program Dashboard** — Acompanha indicações e recompensa clientes automaticamente. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 076 | **Digital Product Marketplace** — Vende ebooks, templates ou cursos com pagamentos integrados. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 077 | **Membership Site Builder** — Cria conteúdo restrito para assinantes pagantes. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 078 | **Event Registration Platform** — Gerencia inscrições de eventos, ingressos e listas de participantes. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 079 | **Client Portal** — Dá aos clientes acesso seguro a documentos e atualizações. | FastAPI + Postgres (full-stack Python) | ⬜ | — |
| 080 | **Proposal Generator** — Cria propostas comerciais profissionais usando templates. | FastAPI + Postgres (full-stack Python) | ⬜ | — |

### 🎨 Criativo / Experimental (081–102) · 1-3 sessões cada

| # | Projeto | Stack | Status | Repo |
|---|---|---|---|---|
| 081 | **AI Dungeon Game** — Jogo de aventura em texto com cenários gerados por IA. | Python + Claude API (Streamlit) | ⬜ | — |
| 082 | **Random Story Generator** — Insira personagens e cenários para gerar narrativas únicas. | Python + Claude API (Streamlit) | ⬜ | — |
| 083 | **AI Meme Caption Generator** — Envie imagens e receba sugestões de legendas humorísticas. | Python + Claude API (Streamlit) | ⬜ | — |
| 084 | **Trivia Quiz Game** — Quiz com múltiplas categorias e pontuação. | Python Web (Flask + HTMX) | ⬜ | — |
| 085 | **Choose-Your-Own-Adventure Generator** — Cria histórias ramificadas com múltiplos finais. | Python + Claude API (Streamlit) | ⬜ | — |
| 086 | **Random Meal Planner** — Cria planos de refeição semanais baseados nas suas preferências. | Python + Claude API (Streamlit) | ⬜ | — |
| 087 | **Habit Tracker with Streaks** — Acompanha hábitos diários e progresso ao longo do tempo. | Python + dbt + Postgres | ⬜ | — |
| 088 | **Dream Journal with AI Analysis** — Registre sonhos e receba análise de padrões. | Python + Claude API (Streamlit) | ⬜ | — |
| 089 | **Virtual Pet Simulator** — Cuide de um pet digital alimentando e brincando com ele. | Python Web (Flask + HTMX) | ⬜ | — |
| 090 | **Daily Challenge Generator** — Receba desafios aleatórios de criatividade ou fitness. | Python + Claude API (Streamlit) | ⬜ | — |
| 091 | **Personality Quiz Builder** — Crie quizzes de personalidade estilo Buzzfeed. | Python Web (Flask + HTMX) | ⬜ | — |
| 092 | **AI Poem Generator** — Cria poemas em vários estilos baseados em temas ou emoções. | Python + Claude API (Streamlit) | ⬜ | — |
| 093 | **Music Playlist Curator** — Gera playlists baseadas em humor ou atividade. | Python + Claude API (Streamlit) | ⬜ | — |
| 094 | **AI Art Prompt Generator** — Gera prompts criativos para artistas e designers. | Python + Claude API (Streamlit) | ⬜ | — |
| 095 | **Debate Topic Generator** — Cria tópicos de discussão para prática ou entretenimento. | Python + Claude API (Streamlit) | ⬜ | — |
| 096 | **Fictional Character Creator** — Gera perfis detalhados de personagens para storytelling. | Python + Claude API (Streamlit) | ⬜ | — |
| 097 | **Random Writing Prompt Generator** — Gera prompts para inspirar escrita criativa. | Python Web (Flask + HTMX) | ⬜ | — |
| 098 | **AI Comic Strip Generator** — Cria ideias de tirinhas com personagens e diálogos. | Python + Claude API (Streamlit) | ⬜ | — |
| 099 | **Fantasy World Builder** — Gera locais, lore e facções para mundos fictícios. | Python + Claude API (Streamlit) | ⬜ | — |
| 100 | **AI Joke Generator** — Gera piadas baseadas em temas, situações ou palavras-chave. | Python + Claude API (Streamlit) | ⬜ | — |
| 101 | **AI Study Quiz Generator** — Insira material de estudo e gere quizzes automaticamente. | Python + Claude API (Streamlit) | ⬜ | — |
| 102 | **Website Meta Tag Generator** — Gera meta titles e descriptions otimizados para SEO automaticamente. | Python + Claude API (Streamlit) | ⬜ | — |


## Ordem sugerida

1. **Aquecimento (001–020)**: fundamentos, ciclo curto, hábito de shipping.
2. **IA na veia (021–040)**: integração com a API do Claude, o multiplicador da série.
3. **Ferramentas (041–060)**: utilidades que aceleram os projetos seguintes.
4. **SaaS (061–080)**: persistência, pagamentos, autenticação.
5. **Criativos (081–102)**: experimentos que rendem os melhores posts.

Dentro de cada bloco a ordem é livre.

## Licença

[MIT](LICENSE) © 2026 Nelson Rodrigues
