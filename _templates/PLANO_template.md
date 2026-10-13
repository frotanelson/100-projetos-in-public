# PLANO — {Nome do Projeto}

> Template da série. Fases padrão: Fundação → [Dados & Schema] → Core (TDD) → Interface → Qualidade → Ship.

## Regras da casa
1. TDD (RED → GREEN → REFACTOR), cobertura ≥ 80%
2. Conventional commits, branch feat/NNN-slug, merge --no-ff
3. Funções <50 linhas, arquivos <800, sem segredos no git
4. code-reviewer + security-reviewer antes do merge

## Fase N — {Nome}
**Objetivo**: {o que entrega}
Passos: 1. ... 2. ...
**Gate de saída**: {critério verificável}
**Checkpoint git**: `git commit -m "feat: ..."`
**Build in public**: anotar 1 aprendizado

## Definition of Done
- [ ] Musts do PRD testados (≥80%)
- [ ] Reviews sem CRITICAL/HIGH
- [ ] README + screenshot
- [ ] Merge na main + status no README mestre
- [ ] Post publicado
