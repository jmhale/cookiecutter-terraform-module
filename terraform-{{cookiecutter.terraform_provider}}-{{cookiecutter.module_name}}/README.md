# terraform-{{cookiecutter.terraform_provider}}-{{cookiecutter.module_name}}

{{cookiecutter.short_description}}

## Variables
| Variable Name | Type | Required |Description |
|---------------|-------------|-------------|-------------|
|`var_name`|`string`|Yes|Example variable required by the Terraform module.|

## Usage

```
module "terraform-{{cookiecutter.terraform_provider}}-{{cookiecutter.module_name}}" {
  source = "git@github.com:{{cookiecutter.github_user}}/terraform-{{cookiecutter.terraform_provider}}-{{cookiecutter.module_name}}.git"
}

```
## Outputs
| Output Name | Description |
|---------------|-------------|
|`output_name`|Example output produced by the Terraform module.|


---
Copyright © {{cookiecutter.release_date.split('-')[0]}}, {{ cookiecutter.full_name }}
