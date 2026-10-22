# Productivity Skills

Repositório-oficina para **produtividade pessoal** com o Claude Code. Abra uma sessão (claude.ai/code ou local) com este repositório selecionado e o Claude descobre automaticamente as skills em `.claude/skills/`.

Curadoria de [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) (licença MIT, ver `LICENSE-claude-skills`), copiada do commit `27cfcd0`.

## O que tem aqui (9 skills)

| Skill | Para que serve |
|---|---|
| `capture` | Transforma um "despejo mental" bagunçado em ações organizadas, sem perder nada. |
| `deep-work` | Planeja o dia em blocos, separando trabalho profundo do raso e protegendo horas de foco. |
| `weekly-review` | Revisão semanal (método GTD): fecha pendências, acha projetos parados, deixa o sistema confiável de novo. |
| `meetings` | Decide se uma reunião vale a pena, calcula quanto ela custa, monta pauta com tempo e resultado esperado. |
| `reflect` | Pausa no meio de uma conversa para reavaliar direção, premissas e vieses. |
| `inbox-setup` | Entrevista única que monta sua base de regras para triagem de e-mail. |
| `inbox-triage` | Faz a triagem da caixa de entrada usando a base criada pelo `inbox-setup`. |
| `handoff` | Resume a conversa atual num documento para outra sessão continuar de onde parou. |
| `fable-goal` | Converte uma descrição solta do que você quer num prompt de objetivo pronto para colar numa sessão nova. |

## Observações

- `inbox-setup`/`inbox-triage` precisam de acesso ao seu e-mail (por exemplo, o conector do Gmail) para trabalhar na caixa real.
- `handoff` pede um local para salvar o documento; em sessões na nuvem, salve dentro deste repositório e faça commit para não perder.

## Como atualizar

Copie de novo as pastas `productivity/<nome>/skills/<nome>` e `productivity/email/skills/*` do repositório de origem para `.claude/skills/`.

Só as skills foram copiadas; agentes e slash commands dos plugins originais não fazem parte deste repositório.
