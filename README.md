# TMStore Catalog

Каталог режимов для лаунчера TMStore.

## Структура

- `modes/modes.json` — индекс каталога.
- `modes/<id>/manifest.json` — манифест сборки режима.
- `modes/<id>/cover.*` — обложка режима.
- `modes/<id>/build.zip` — сборка режима.
- `modes/<id>/build.zip.001`, `.002`, ... — части большой сборки.

## Подключение

Лаунчер по умолчанию загружает каталог по адресу:

```text
https://raw.githubusercontent.com/tommy-whinston/TMStore-Catalog/main/modes/modes.json
```

Адрес можно изменить в настройках лаунчера в поле «Источник каталога».

## Публикация

TMPublisher пишет каталог и файлы режимов в этот репозиторий через GitHub API.
Позже публикация будет переведена на API магазина.
