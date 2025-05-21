# Convenção de Branches e Commits

Este guia define o padrão oficial de nomenclatura de branches e mensagens de commit adotado pela equipe de tecnologia. O objetivo é garantir organização, rastreabilidade e consistência no desenvolvimento.

---

## Padrão de Nome de Branch

### Formato

tipo/id-descricao

### Componentes

- `<tipo>`: tipo da branch:
  - `feature` → nova funcionalidade
  - `bugfix` → correção de bug
  - `hotfix` → correção urgente
  - `chore` → tarefas técnicas (configs, scripts, manutenção)
  - `refactor` → refatorações sem mudança de comportamento
  - `test` → testes
  - `docs` → documentação

- `<id>`: identificador do card no Trello (ex: 1234)

- `<descricao>`: descrição curta e clara em kebab-case

### Exemplos

feature/1234-login-social
bugfix/2048-corrige-token-expirado
refactor/3001-melhora-estrutura-css
chore/4123-atualiza-dependencias
docs/1099-ajusta-readme

---

## Padrão de Commit

Utilizamos Commits Semânticos para manter um histórico de mudanças claro e útil.

### Formato

tipo(escopo): mensagem no imperativo [id]

- `<tipo>`: intenção da mudança (veja tabela abaixo)
- `<escopo>`: área do código afetada (opcional, mas recomendado)
- `<mensagem>`: ação direta, no imperativo (ex: adiciona, corrige, atualiza)
- `[<id>]`: identificador da tarefa entre colchetes (opcional, mas recomendado)

### Tipos de Commit

| Tipo     | Descrição                                                |
| -------- | ------------------------------------------------------- |
| feat     | Criação de nova funcionalidade                           |
| fix      | Correção de bugs                                        |
| style    | Ajustes visuais ou de formatação (espaços, indentação)  |
| refactor | Refatoração interna sem alteração de funcionalidade     |
| test     | Adição ou modificação de testes                          |
| docs     | Alterações na documentação                               |
| chore    | Tarefas técnicas (configs, scripts, ferramentas auxiliares) |
| perf     | Melhorias de performance                                 |
| build    | Mudanças que afetam o sistema de build ou dependências externas |
| ci       | Alterações em arquivos/scripts de integração contínua   |

### Exemplos

feat(auth): adiciona login com Google [1234]
fix(api): corrige erro na validação de token [2048]
refactor(ui): melhora organização dos componentes [3001]
chore: atualiza dependências do projeto [4123]
docs(readme): adiciona instruções de execução [1099]

> O identificador da tarefa (`[1234]`) pode ser incluído no início, no final ou entre parênteses, desde que seja consistente.

---

## Boas Práticas

- Sempre crie a branch com base no padrão `<tipo>/<id>-<descricao>`
- Use o identificador da tarefa nas branches e commits para facilitar rastreamento
- Commits devem ser pequenos, frequentes e claros
- Use o tempo verbal no imperativo nas mensagens de commit
- Mantenha a descrição do commit objetiva e clara
