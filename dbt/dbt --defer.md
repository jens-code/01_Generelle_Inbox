---
Bereich: dbt
tags:
  - development
  - dbt
---
# Workflow

## Kompiliere den "prod" Code
```shell
> dbt compile --target-pat target_prod -t prod
```

## Nutze den kompilierten "prod" code
```shell
> dbt run --defer --state target_prod --favor-state
```

Hier kann man die üblichen [[dbt --select|Selektoren]] nutzen.
