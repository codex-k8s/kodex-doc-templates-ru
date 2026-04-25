# kodex doc templates

Публичный репозиторий шаблонов документации для проектов `kodex`.

## Назначение

Репозиторий содержит базовые шаблоны продуктовой, архитектурной, delivery, QA и SRE-документации.

## Связанные репозитории

- `github.com/codex-k8s/kodex` — основная платформа.
- `github.com/codex-k8s/kodex-guidelines-common-ru` — общие инженерные правила.
- `github.com/codex-k8s/kodex-guidelines-go-ru` — правила для Go.
- `github.com/codex-k8s/kodex-guidelines-vue-ru` — правила для Vue и TypeScript.

## Использование

До внедрения штатного импорта руководящих пакетов основной репозиторий `github.com/codex-k8s/kodex` хранит локальную копию этих файлов в `docs/templates/**`.

Изменения в этом репозитории и локальной копии в `kodex` должны синхронизироваться через PR в соответствующие репозитории.
