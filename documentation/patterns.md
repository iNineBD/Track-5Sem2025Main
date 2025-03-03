# Padronização de Projetos

## Nomeação de Branches

Formato: `{tipo}/{descricao-resumida}-{código da tarefa no Jira}`

Tipos permitidos:

- `feature/` - Para novas funcionalidades ao projetos, componentes e afins.
- `bugfix/` - Para correções de bugs.
- `hotfix/` - Para correções URGENTES em produção.
- `improvement/` - Para melhoria de uma feature já existente, seja de performance, escrita, layout, etc.

Exemplo: `feature/implementacao-login-TRK-001`

![](https://github.com/user-attachments/assets/ce5856ba-1732-4072-8ca4-9fc76b0f63ff)

## Mensagens de Commits

Formato: `{tipo}: {descrição curta}`

Tipos permitidos:

- `feat:` - Implementação de nova funcionalidade.
- `fix:` - Correção de bug ou problemas no código.
- `doc:` - Alterações na documentação.
- `style:` - Ajuste de formatação (sem impacto funcional).
- `refactor:` - Refatoramento de código.
- `test:` - Adição/atualização de testes.
- `chore:` - Tarefa sem impacto direto no código fonte, ferramentas, configurações ou bibliotecas.

Exemplo: `feat: Implementação do login com OAuth`

## Nomeação de Tabelas no Banco de Dados

- Utilizar o padrão `snake_case`, no singular.
- Evitar abreviações.

Exemplo: `usuarios`, `pedidos`, `produtos`

## Nomeação de Colunas no Banco de Dados

- Utilizar `snake_case`, no singular.
- Utilizar prefixos padronizados para chaves estrangeiras (`id_` seguido do nome da tabela referenciada).

Exemplo: `id_usuario`, `nome_completo`, `data_criacao`

## Títulos de Pull Requests

Formato: `[Tipo] Descrição curta da alteração`

Tipos permitidos:

- `[Feature]` - Nova funcionalidade.
- `[Fix]` - Correção de bug.
- `[Docs]` - Documentação.
- `[Refactor]` - Refatoramento de código.
- `[Chore]` - Manutenção interna.

Exemplo: `[Feature] Implementação do login com OAuth`

## Títulos para Tags de Versão

Formato: `sprint - {versão}`

Exemplo: `sprint - 1`

## Nomeação de Variáveis

- Utilizar `camelCase` para nomes de variáveis.
- Evitar abreviações.
- Utilizar nomes descritivos.
- Utilizar nomes em inglês.
- Utilizar nomes que representem o conteúdo da variável.

Exemplo: `nomeCompleto`, `dataCriacao`, `usuarioLogado`

## Comentários no Código

- Pelos menos um comentário por função.
- Devem ser objetivos e explicativos.
- Devem ser escritos em inglês.

Exemplo:

```golang
// getUserByID busca um usuário no banco de dados pelo ID.
func getUserByID(id int) (*User, error) {
    // ...
}
```