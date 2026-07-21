# 📚 Gestão de Projetos — Templates

Biblioteca reutilizável de artefatos de Gestão de Projetos baseada em **PMBOK**, **Scrum**, **Kanban** e **ITIL**.

![License](https://img.shields.io/badge/license-MIT-blue) ![Made with](https://img.shields.io/badge/Made%20with-Markdown-lightgrey)

## 📂 Estrutura

```
docs/
 ├── 01-project-charter.md     Termo de Abertura (TAP)
 ├── 02-stakeholders.md        Matriz RACI + Poder × Interesse
 ├── 03-escopo-eap.md          EAP / WBS
 ├── 04-cronograma.md          Gantt (Mermaid)
 ├── 05-riscos.md              Matriz de Riscos
 ├── 06-comunicacao.md         Plano de Comunicação
 ├── 07-licoes-aprendidas.md   Retrospectiva
 └── 08-encerramento.md        Termo de Encerramento (TEP)
diagrams/
 ├── fluxo-processo.mmd
 ├── eap.mmd
 └── gantt.mmd
.github/
 ├── ISSUE_TEMPLATE/           user-story, bug, risco, mudança
 └── pull_request_template.md
```

## 🚀 Como usar

1. Faça um fork ou clone deste repositório
2. Copie a pasta `docs/` para o seu novo projeto
3. Preencha cada template seguindo os comentários `<!-- ... -->`
4. Ative os templates de issue copiando `.github/` para o repo destino

## 🧭 Quando usar cada template

| Fase | Template |
| :-- | :-- |
| Iniciação | `01-project-charter.md`, `02-stakeholders.md` |
| Planejamento | `03-escopo-eap.md`, `04-cronograma.md`, `05-riscos.md`, `06-comunicacao.md` |
| Execução / Monitoramento | Issues (user story, risco, mudança) |
| Encerramento | `07-licoes-aprendidas.md`, `08-encerramento.md` |

## 📄 Licença

MIT — sinta-se livre para reutilizar em seus projetos.
