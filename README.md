# MOST v4.4 — External Pitch Deck

Публичная версия презентации MOST: закрытая trust-сеть, которая превращает доверие, запросы и связи в управляемые сделки.

## Что изменено относительно v4.3

- Убран внутренний `handoff`/dev-блок из публичной версии.
- Убран блок “Что исправлено” — вместо него внешний pitch.
- Сделан настоящий slide-mode: 8 полноэкранных кадров, клавиатура, progress, сохранение текущего слайда.
- Детали открываются по клику `детали` / клавише `D` в боковой панели.
- Усилена бизнес-рамка: проблема → trust graph → deal brief → route map → deal room → деньги → 30-дневный пилот.
- Старый v4.3 сохранён локально как `v4.3-internal-handoff.html`.

## Слайды

1. Тезис: доверие должно доходить до сделки.
2. Проблема: связи есть, операционной системы нет.
3. Trust graph: приватный профиль полезности.
4. Deal brief: запрос становится объектом.
5. Route + intro: не рассылка, а тёплый маршрут.
6. Deal Room: чат превращается в предмет сделки.
7. Business model: license / curator / upside.
8. Pilot: 30-дневная проверка Go/Kill.

## Локально

```bash
cd /Users/vitalij/Desktop/most-hermes-v3-ui-redesign/v4.3-visual-sense-deck
python3 -m http.server 5187 --bind 127.0.0.1
```

Открыть:

```text
http://127.0.0.1:5187/
```

## GitHub / live preview

Репозиторий:

```text
https://github.com/vitaliy-demidov/most-v4-3-visual-sense-deck
```

GitHub Pages:

```text
https://vitaliy-demidov.github.io/most-v4-3-visual-sense-deck/
```

## Файлы

```text
index.html                     # v4.4 external pitch
v4.3-internal-handoff.html      # архив предыдущей внутренней версии
```
