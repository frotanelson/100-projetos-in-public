# Build in Public — Guia da Série

> Como esta série é construída e publicada. Vale para todos os 102 projetos.

## Modelo de publicação

- **Esta vitrine** (`100-projetos-in-public`): roadmap, guia, templates e a tabela com o link de cada projeto entregue.
- **Um repositório público por projeto** (`frotanelson/NNN-slug`): criado apenas quando o projeto é entregue, com código, testes e README com aprendizados.
- O planejamento e o trabalho em andamento ficam em um repositório privado; nada de PRD/plano de projetos futuros é exposto.

## Cadência

- **Ritmo alvo**: 2–3 projetos/semana nos iniciantes; 1/semana nos SaaS. Série completa em ~12 meses.
- **Regra de ouro**: shipped > perfeito. O Definition of Done do plano de cada projeto é o limite, sem gold-plating.
- **Sessões**: usar o Pomodoro da própria série (projeto 018) quando existir. Dogfooding é conteúdo.

## O ciclo de cada projeto

```text
PRD (revisar 15min) → PLANO Fase 1..N (checkpoint git por fase) → Ship (repo público) → Tabela da vitrine → Post
```

1. **Antes de codar**: ler o PRD, ajustar o que mudou de ideia, validar a Open Question de escopo.
2. **Durante**: cada fase do plano termina com commit + 1 aprendizado anotado no README do projeto.
3. **Ao entregar**: criar o repo público `frotanelson/NNN-slug`, atualizar a tabela da vitrine (status ✅ + link) e publicar o post.

## Template de post (por projeto)

```markdown
# Projeto NNN/102: {Nome} — {gancho: o problema em uma frase}

**O problema**: {2-3 frases, por que existe}
**O processo**: {como foi construir com Claude Code — prompts que funcionaram,
onde a IA brilhou, onde precisei assumir o volante}
**O resultado**: {screenshot/GIF + o que faz + link do repo do projeto}
**O que aprendi**: {1-3 aprendizados honestos, técnicos ou de processo}
**Números**: {tempo real gasto, sessões, linhas, cobertura}

Próximo: {teaser do projeto seguinte}
```

## Formatos derivados

| Canal | Formato | Frequência |
|-------|---------|-----------|
| Blog próprio (projeto 020) | Post completo | 1 por projeto |
| LinkedIn | Resumo com aprendizado principal | 1 por projeto |
| X/Twitter | Thread do processo | projetos com boa história |
| GitHub | Esta vitrine + um repo por projeto | contínuo |

## Métricas da série (revisar mensalmente)

- Projetos entregues / mês
- Posts publicados / projetos entregues (alvo: 100%)
- Tempo médio por categoria (estimado vs real — publicar a diferença é ótimo conteúdo)
- Módulos reusados entre projetos (a série compõe)

## Princípios

1. **Documentar o processo real**, incluindo o que deu errado. Falha documentada é o post com mais engajamento.
2. **Código público na entrega** — sem "vou limpar antes de publicar": o repo já nasce limpo, sem segredos.
3. **Segurança inegociável** — revisão de segurança antes de todo merge; segredo vazado = rotacionar na hora.
4. **A IA é par, não fantasma** — os prompts usados fazem parte do conteúdo.
