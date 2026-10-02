# DeltaSnake2D

Companion к [Snake2D](https://github.com/LuntikVisuals/Snake2D).

## Идея
- Отдельное приложение/тулза создаёт **свои** файлы на телефоне
- И **совместимые** файлы в каталоге игры: `files/snake2d/companion/`
- Сейчас `source: cheat-v1` — позже станет `tools-v2` (визуалы/утилиты)
- Античит Snake2D читает `manifest.json` и помечает прогоны

## manifest.json (пример)
```json
{
  "protocol": 1,
  "name": "DeltaSnake2D",
  "source": "cheat-v1",
  "version": "0.1.0"
}
```

## Установка клиента игры
APK Snake2D — из Releases (как LuntikTerminal → клиент). Ставить **поверх**, не удаляя — прогресс сохраняется.
