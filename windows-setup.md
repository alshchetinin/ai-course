# Установка Claude Code на Windows

## Шаг 1: Git for Windows (обязательно!)

Скачайте и установите: https://git-scm.com/download/win

При установке оставьте все настройки по умолчанию.

## Шаг 2: Windows Terminal

Скачайте из Microsoft Store: найдите "Windows Terminal".
Если уже установлен — отлично, ничего делать не нужно.

## Шаг 3: Claude Code

Откройте Windows Terminal (PowerShell) и выполните:

```powershell
irm https://claude.ai/install.ps1 | iex
```

**После установки — закройте и откройте терминал заново!**

Если команда `claude` не работает — перезапуск терминала решает проблему в 90% случаев.

## Шаг 4: Проверка

```powershell
claude --version
```

Если видите версию — всё работает.

## Возможные проблемы

| Проблема | Решение |
|----------|---------|
| `claude is not recognized` | Перезапустить терминал |
| PowerShell-установщик не работает | Попробовать CMD: `curl -fsSL https://claude.ai/install.cmd -o install.cmd && install.cmd` |
| Вставка скриншотов не работает | Использовать **Alt+V** (не Ctrl+V!) |

## Важно

- Нужна подписка Claude Pro ($20/мес) или Max ($100/мес)
- Бесплатный план НЕ поддерживает Claude Code
