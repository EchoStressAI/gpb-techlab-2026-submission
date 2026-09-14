# Документация EchoStressAI · GPB TechLab 2026

Этот каталог — навигационная точка публичной документации решения. Репозиторий построен по принципу **public integration / private runtime**: публично описываются архитектура, интерфейсы, сценарии использования, валидация и ограничения; закрытые исследовательские пайплайны, датасеты, веса моделей и универсальная интегральная методология EchoStressAI в Git не публикуются.

## Быстрый маршрут

| Если нужно | Документ |
|---|---|
| Понять задачу и состав решения | [PROJECT_OVERVIEW.md](PROJECT_OVERVIEW.md) |
| Понять общую методологию без закрытых формул | [METHODOLOGY.md](METHODOLOGY.md) |
| Разобраться в CASE 1 | [CASE1_MODEL_CARD.md](CASE1_MODEL_CARD.md) |
| Разобраться в CASE 2 | [CASE2_MODEL_CARD.md](CASE2_MODEL_CARD.md) |
| Понять экспертную и научную проверку | [EXPERT_REVIEW_AND_VALIDATION.md](EXPERT_REVIEW_AND_VALIDATION.md) |
| Понять объяснения модели | [EXPLAINABILITY.md](EXPLAINABILITY.md) |
| Интегрироваться с API | [API_REFERENCE.md](API_REFERENCE.md) |
| Развернуть сервис | [DEPLOYMENT.md](DEPLOYMENT.md) |
| Провести демонстрацию | [DEMO_GUIDE.md](DEMO_GUIDE.md) |
| Понять требования к данным и ИБ | [DATA_PRIVACY_SECURITY.md](DATA_PRIVACY_SECURITY.md) |
| Понять ограничения и корректную интерпретацию | [LIMITATIONS_AND_RESPONSIBLE_USE.md](LIMITATIONS_AND_RESPONSIBLE_USE.md) |
| Воспроизвести техническую часть | [REPRODUCIBILITY.md](REPRODUCIBILITY.md) |
| Решить типовые проблемы | [TROUBLESHOOTING.md](TROUBLESHOOTING.md) |
| Проверить готовность перед показом | [ACCEPTANCE_CHECKLIST.md](ACCEPTANCE_CHECKLIST.md) |

## Уже существующие технические документы

- [ARCHITECTURE.md](ARCHITECTURE.md) — архитектурная граница public/private runtime.
- [RUNTIME_CONTRACT.md](RUNTIME_CONTRACT.md) — контракт локальных model runtime-компонентов.
- [PUBLIC_REPOSITORY_POLICY.md](PUBLIC_REPOSITORY_POLICY.md) — что допустимо и недопустимо публиковать.

## Принципы документации

1. **Никаких фиктивных результатов.** Если runtime отсутствует, API сообщает об этом явно.
2. **Никаких скрытых подмен метрики.** Экспериментальные, экспертные и production-результаты разделяются.
3. **Никакой ретроспективной подгонки.** Контрольные и экспертные разборы не используются для «улучшения» уже рассчитанной метрики задним числом.
4. **Разделение сигнала и интерпретации.** Акустический/эмоциональный сигнал не является медицинским диагнозом и не равен автоматически психологическому конструкту.
5. **Минимально необходимая публичность.** Публикуется то, что нужно для понимания и интеграции решения, а не внутреннее know-how EchoStressAI.
