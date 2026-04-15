# Estrutura Recomendada do Repositório da Disciplina

Esta estrutura foi reduzida para o essencial. A ideia não é engessar a disciplina, mas fornecer um ponto de partida consistente e fácil de manter.

```text
/
├── README.md
├── PLANO_DISCIPLINA.md
├── CRONOGRAMA.md
├── AVALIACAO.md
├── REFERENCIAS.md
├── FAQ.md
├── POLITICA_GITHUB.md
├── POLITICA_IA.md
├── PROMPTS_IA.md
├── VSCODE_EXTENSOES.md
├── orientacoes-institucionais.md
├── .gitignore
│
├── docs/
│   ├── ppc/
│   └── planos_old/
│
├── aulas/
│   └── README.md
│
├── ead/
│   └── README.md
│
├── atividades/
│   └── README.md
│
├── rubricas/
│   └── README.md
│
├── templates/
│   ├── README.md
│   ├── README-atividade.md
│   ├── relatorio-sigaa.md
│   └── resumo-encontro.md
│
├── exemplos/
│   └── README.md
│
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── duvida.md
    │   ├── erro.md
    │   └── entrega.md
    └── PULL_REQUEST_TEMPLATE.md
```

## O que cada parte faz

- `README.md`: apresenta o repositório da disciplina e orienta o estudante.
- `PLANO_DISCIPLINA.md`: documento-base do plano de curso.
- `CRONOGRAMA.md`: organiza os 15 encontros, sem datas fixas.
- `AVALIACAO.md`: descreve princípios, instrumentos e critérios.
- `REFERENCIAS.md`: concentra bibliografia e materiais complementares.
- `FAQ.md`: responde dúvidas recorrentes sobre fluxo, entrega, IA e organização.
- `POLITICA_GITHUB.md`: formaliza o fluxo de fork, branch, commit, PR e entrega.
- `POLITICA_IA.md`: define o uso pedagógico e ético de IA.
- `PROMPTS_IA.md`: guarda prompts-base para apoio docente e atividades com IA permitida.
- `VSCODE_EXTENSOES.md`: recomenda extensões por contexto de disciplina.
- `orientacoes-institucionais.md`: espaço para registrar normas locais ou ajustes administrativos.

## Diretórios de trabalho

- `aulas/`: roteiros, quadros, práticas, slides visuais e materiais por encontro.
- `ead/`: vídeos, materiais e atividades quando houver carga EAD no PPC.
- `atividades/`: listas, laboratórios, projeto integrador e etapas.
- `rubricas/`: critérios detalhados de correção por tipo de atividade.
- `templates/`: modelos curtos reutilizáveis por professor e estudantes.
- `exemplos/`: códigos comentados e pequenos projetos demonstrativos.
- `docs/`: PPC, planos antigos, documentos de apoio e versões entregues.

## Observações importantes

- Nem toda disciplina precisará usar todos os diretórios.
- Em disciplinas sem carga EAD, `ead/` pode ser mantido apenas para vídeos complementares.
- O material de aula pode ficar simultaneamente no GitHub e no SIGAA, mas o GitHub continua sendo o eixo de organização da disciplina.
