# Apache-role

Installeert Apache op Ubuntu 24.04, configureert de hostname
en stelt automatisch opstarten van de service in.

## Variabelen

- apache_package: apache2
- apache_service: apache2

## Voorbeeld

```yaml
---
- name: Apache installeren
  hosts: webservers
  become: true

  roles:
    - avi1505.apache
```

## Licentie

MIT