# Ansible Workstation

Playbook e roles que uso para provisionar minha workstation.

## Requisitos

- Ubuntu 18.04+
- Ansible 2.4+

## Uso

```shell
$ ansible-pull -U https://github.com/elvisgs/ansible-workstation --ask-become-pass --ask-vault-pass
```

Não é necessário especificar o playbook; o comando `ansible-pull` executa o playbook `local.yml` por padrão.

Todas as roles possuem tags. Para executar e/ou ignorar roles/tags especifícias, use os argumentos `--tags` e `--skip-tags`.