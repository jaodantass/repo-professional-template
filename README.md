# Repo Professional Template

Professional starter template for portfolio and production-like study projects.

## Purpose

This repository provides a reusable baseline for:
- Consistent project structure
- Contribution workflow
- Issue and PR standards
- Engineering hygiene from day one

## Naming Convention

Use the following pattern for new repositories:

`fs-<domain>-<service>`

Examples:
- `fs-tasks-api`
- `fs-orders-service`
- `fs-analytics-dashboard`
- `fs-portfolio-web`

## Branch Strategy

- `main`: stable branch
- `feat/<short-description>`: new feature
- `fix/<short-description>`: bug fix
- `chore/<short-description>`: maintenance, docs, tooling

Examples:
- `feat/auth-jwt`
- `fix/pagination-metadata`
- `chore/update-readme`

## Default Structure

```text
.
├── .github/
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md
├── docs/
└── README.md
```

## Workflow

1. Open or create an issue.
2. Move issue status to `In Progress`.
3. Create a branch from `main` using the branch strategy.
4. Implement changes and open a pull request.
5. Move issue to `Review` while PR is open.
6. After merge and validation, move issue to `Done`.

## How To Use This Template

1. Click **Use this template** on GitHub.
2. Create a new repository from this template.
3. Rename it following the naming convention.
4. Update the README for the new project scope.
5. Start with a first issue and link work to a PR.

## Definition of Ready (New Repositories)

Before coding features, ensure:
- Repository name follows the naming convention
- README is updated for project scope
- Issue and PR templates are available
- Branch strategy is clear
- Basic CI is configured

## Definition of Done (Week 1 Baseline)

- Repository created and documented
- Naming and branching conventions defined
- Base folder structure created
- Team workflow documented

## License

Choose a license when creating each project (for portfolio projects, MIT is a common default).
