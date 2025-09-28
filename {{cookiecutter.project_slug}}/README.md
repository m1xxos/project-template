<h1 align="center">
  <br>
  <a href="https://github.com/m1xxos/homelab">
    <img src="assets/icon.png" alt="Logo" width="80" height="80">
  </a>
  <br>
  {{ cookiecutter.project_name }}
  <br>
</h1>

<h4 align="center">{{ cookiecutter.description }}</h4>

## How to use
Steps to get started

1. Generate new logo at https://ray.so/icon
1. Add values to terraform/yc.tfstate
2. Init terraform state with command

```bash
terraform init -backend-config=yc.auto.tfvars
```
