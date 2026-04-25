# kodex doc templates

Публичный репозиторий шаблонов документации для проектов и пакетов, разрабатываемых через платформу.

## Назначение

Репозиторий содержит базовые шаблоны продуктовой, архитектурной, delivery, QA и SRE-документации.

## Связанные репозитории

- `github.com/codex-k8s/kodex` — основная платформа.
- `github.com/codex-k8s/kodex-guidelines-common-ru` — общие инженерные правила.
- `github.com/codex-k8s/kodex-guidelines-go-backend-ru` — правила для Go backend.
- `github.com/codex-k8s/kodex-guidelines-vue-frontend-ru` — правила для Vue и TypeScript frontend.

## Использование

До внедрения штатного импорта руководящих пакетов основной репозиторий `github.com/codex-k8s/kodex` хранит локальную копию этих файлов в `docs/templates/**`.

Изменения в этом репозитории и локальной копии в `kodex` должны синхронизироваться через PR в соответствующие репозитории.
