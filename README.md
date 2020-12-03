# pre-commit-django-migrations
Pre-commit hook to check if there are migrations that need creation

Example .pre-commit-config.yaml:

```
repos:
  - repo: https://github.com/waveFrontSet/pre-commit-django-migrations
    rev: master
    hooks:
    - id: pre-commit-django-migrations
```
