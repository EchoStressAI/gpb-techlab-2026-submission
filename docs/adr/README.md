# Architecture Decision Records

ADR фиксируют решения, которые определяют публичный integration contract. Они нужны, чтобы позднее не «исправить» важное архитектурное ограничение случайным рефакторингом.

| ADR | Решение | Статус |
|---|---|---|
| [ADR-001](ADR-001-public-integration-private-runtime.md) | public integration / separate local runtime | Accepted |
| [ADR-002](ADR-002-fixed-analysis-horizons.md) | CASE 1 = 60 sec, CASE 2 = 180 sec | Accepted |
| [ADR-003](ADR-003-fail-closed-runtime.md) | no fake score when runtime unavailable | Accepted |
| [ADR-004](ADR-004-quality-separate-from-score.md) | quality/evidence separate from model score | Accepted |
| [ADR-005](ADR-005-expert-review-not-ground-truth.md) | expert review is not automatic ground truth | Accepted |
| [ADR-006](ADR-006-public-safe-adapter.md) | bridge existing private backend through sanitized adapter | Accepted |

## Формат

Каждый ADR содержит:

- Context;
- Decision;
- Consequences;
- Alternatives considered;
- Status.

ADR описывает решение, но не раскрывает закрытые model formulas или данные.
