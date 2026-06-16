# github-workflows

Coleção de workflows reutilizáveis do GitHub Actions para infraestrutura e desenvolvimento.

Collection of reusable GitHub Actions workflows for infrastructure and development.

## Workflows

- `terraform-ci.yml` - Validação, formatação e segurança para Terraform / Terraform validation, formatting and security

## Como usar / How to Use

```yaml
jobs:
  terraform:
    uses: raafa001/github-workflows/.github/workflows/terraform-ci.yml@main
    with:
      terraform_version: 1.9.0
      working_directories: '["terraform/env/prod"]'
```

## Licença / License

MIT
