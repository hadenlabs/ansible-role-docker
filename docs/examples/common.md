<!-- Space: AnsibleRoleDocker -->
<!-- Parent: Project -->
<!-- Title: Project Examples -->

<!-- Label: Examples -->
<!-- Include: docs/disclaimer.md -->
<!-- Include: ac:toc -->

## packages

To run this playbook with default settings, for install package like this:

```yaml
- hosts: all
  vars:
    docker_install_compose: true
    docker_compose_version: '1.29.0'

  roles:
    - devops-toolkit.docker
```
