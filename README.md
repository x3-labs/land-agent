# land-agent

Агент для Claude Code — помогает создавать лендинги для быстрого
тестирования маркетинговых идей.

## Быстрый старт

1. Клонировать репозиторий
2. Открыть папку в Claude Code
3. Написать `/new-landing` и ответить на вопросы

## Структура репозитория

```
.claude/
  CLAUDE.md              — инструкции для Claude Code
  commands/
    new-landing.md       — команда /new-landing

prompts/
  skill-forms.md         — скилл подключения форм
  examples/
    variables.md         — стандартные названия переменных
```

## Стек

HTML + CSS переменные + Vanilla JS + Google Fonts.
Без фреймворков. Без сборки. Один файл.

## Скрипт передачи форм

[hook-form.js](https://github.com/x3-labs/hook-form) — отдельный репозиторий x3-labs/hook-form.
Подключается через jsDelivr, версионируется независимо.

## Лицензия

Business Source License 1.1.
Коммерческое использование требует лицензии.
