<h1 align="center">Project Standardization</h1>

<p align="center">
    <a href="#context">Context</a> |
    <a href="#branch-naming">Branch Naming</a> |
    <a href="#commit-messages">Commit Messages</a> |
    <a href="#pull-request">Pull Request</a> |
    <a href="#naming-database">Naming Database</a> |
    <a href="#tags">Tags</a> |
    <a href="#variable-naming">Variable Naming</a> |
    <a href="#comments">Comments</a> |
    <a href="#environment-variables">Environment Variables</a>
</p>

<span id="context">

## Context
This document aims to standardize development practices across all project repositories, promoting consistency, readability, and efficient collaboration among team members. The guidelines described here apply to all development stakeholders, including frontend, backend, and data.

<span id="branch-naming">

## Branch Naming
### Format:
- `{type}/{Jira issue code}-{brief-description}`

### llowed types:
- `feature/` - For new features to projects, components, etc.
- `fix/` - For feature fixes.
- `bugfix/` - For bug fixes.
- `hotfix/` - For URGENT fixes in production.
- `improvement/` - For improvements to an existing feature, whether it be performance, writing, layout, etc.

### Example:
- `feature/TRK-16-standards-documentation-and-main-repository`

![](https://github.com/user-attachments/assets/ce5856ba-1732-4072-8ca4-9fc76b0f63ff)

<span id="commit-messages">

## Commit Messages
### Format:
- `{type}: {short description}`

### Allowed types:
- `feat:` - Implementation of new functionality.
- `fix:` - Bug fix or code issues.
- `doc:` - Documentation changes.
- `style:` - Formatting adjustment (no functional impact).
- `refactor:` - Code refactoring.
- `test:` - Addition/update of tests.
- `chore:` - Task with no direct impact on source code, tools, configurations or libraries.

### Example:
- `feat: Implementation of OAuth login`

<span id="pull-request">

## Pull Request Titles
### Format:
- `[Type] Short description of the change`

### Allowed types:
- `[Feature]` - New functionality.
- `[Fix]` - Bug fix.
- `[Docs]` - Documentation.
- `[Refactor]` - Code refactoring.
- `[Chore]` - Internal maintenance.

### Example:
- `[Feature] Implementation of OAuth login`

## Reviews and Pull Requests
- All new features must be submitted via Pull Request (PR).
- The PR must be reviewed by at least one team member before merging.
- Add the Jira task link in the PR description.
- Mark the responsible team as reviewer.

<span id="naming-database">

## Naming Database Tables
- Use the `snake_case` pattern, in the singular.
- Avoid abbreviations.

### Example:
- `users`, `orders`, `products`

## Naming Database Columns
- Use `snake_case`, in the singular.
- Use standardized prefixes for foreign keys (`id_` followed by the name of the referenced table).

### Example:
- `user_id`, `full_name`, `creation_date`

<span id="tags">

## Titles for Release Tags
### Format:
- `sprint - {release}`

### Example:
- `sprint - 1`

<span id="variable-naming">

## Variable Naming
- Use `camelCase` for variable names.
- Avoid abbreviations.
- Use descriptive names.
- Use names in English.
- Use names that represent the variable content.

### Example:
- `nomeCompleto`, `dataCriacao`, `usuarioLogado`

<span id="comments">

## Comments in the Code
- At least one comment per function.
- They must be objective and explanatory.
- They must be written in English.

### Example:
```golang
// getUserByID searches for a user in the database by ID.
func getUserByID(id int) (*User, error) {
// ...
}
```

<span id="environment-variables">

## Default for Environment Variables
- Use `UPPER_SNAKE_CASE`
- Prefix with project name if necessary
- Never version real `.env` files, only a `.env.example`
