# Ansible Role: k8s_traefik

[![Lint](https://github.com/dcjulian29/ansible-role-k8s_traefik/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-k8s_traefik/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-k8s_traefik.svg)](https://github.com/dcjulian29/ansible-role-k8s_traefik/issues)

This an Ansible role to install Traefik Chart into a kubernetes cluster.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.k8s_traefik
  src: https://github.com/dcjulian29/ansible-role-k8s_traefik.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
