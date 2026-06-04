# Продукты

## Sorrel Hub

Главный бренд и зонтик для всей экосистемы.

Исторически Sorrel Hub начался как Discord-сервер для Roblox-игры `Щавель обби` и будущих плейсов Winner. Это важная деталь, потому что старый Sorrel Hub был не про script hub в нынешнем смысле. Он был больше про комьюнити вокруг игры и будущих Roblox-проектов.

Позже, примерно в сентябре-октябре 2025, Sorrel Hub начал превращаться в проект под Roblox scripts, web, backend/API и другие dev-направления.

Направления:

- web dashboard
- backend/API
- Luau / Roblox scripts
- UI/UX
- AI tools
- desktop/tools experiments

## Sorrel Hub: NextGen

Текущая эпоха после перезапуска в ноябре 2025.

Текущий Sorrel Hub: NextGen был создан Winner и Lovey0x. Lox / `lox_228` относится к pre-NextGen эпохе как co-owner старого Sorrel Hub до конца той эпохи.

`NextGen` лучше понимать как название chapter/reboot. В будущем публичное название может снова стать просто `Sorrel Hub`.

## Web Dashboard

Web-слой Sorrel Hub отвечает за сайт, аккаунт, подключенные сервисы и будущий dashboard.

Текущий web-подход движется в сторону React / Next.js.

Планируемая доменная структура:

- `sorrelhub.xyz` - основной сайт
- `api.sorrelhub.xyz` - API и loader
- `aibot.sorrelhub.xyz` - Sorrel AI
- кабинет - часть основного сайта/dashboard-направления

Кабинет пока не выносится в отдельный subdomain, и это больше не активная архитектурная цель.

## WinWare

WinWare - Roblox/Luau направление с фокусом на HvH, Visuals и связанные модули.

Если объяснять проще, WinWare не стоит описывать только как farming script. У него была PVE-история, но текущий смысл направления шире: визуалы, HvH-логика, gameplay modules, UI и Roblox/Luau эксперименты.

Известные этапы:

- `WinWare:PVE` - первая версия, создана 2025-11-23.
- `WinWare Pre-Alpha Test` - объявлен 2025-12-31 и снова открыт 2026-01-01.

`WinWare:PVE` был farming script для `Build A Boat For Treasure`, использовал `Luna UI`, имел key system и сейчас discontinued.

## LoveyWare

LoveyWare - направление Lovey0x, а не просто "один скрипт".

Если WinWare описывать через HvH/Visuals, то LoveyWare лучше описывать как bypass-oriented направление и набор модулей вокруг этого подхода. Это часть текущей Sorrel Hub: NextGen истории, потому что Lovey0x является co-owner текущей эпохи, а не просто автором отдельного файла.

Факты:

- опубликован 2025-11-24
- первая цель: `Violence District`
- 2025-12-08 получил новую key system и больше модулей
- 2026-01-01 объявлено, что LoveyWare больше не будет работать с `Violence District`
- новый фокус: менее популярные или более простые игры

## TargetWare

TargetWare вырос из `predict tp` и `target esp`.

Факты:

- официально создан и опубликован 2026-04-18
- связан с Roblox gameplay modifications и script analysis
- ранние тесты predict tp стали частью истории знакомства Winner и Lovey0x

## Sorrel AI

Sorrel AI - AI-бот в экосистеме Sorrel Hub.

Домен:

```txt
aibot.sorrelhub.xyz
```

Первый запуск был 2025-12-14. Исторически это был AI-бот без ограничений и предупреждений, который писал любой код. Он работал недолго и иногда запускался вручную.

## ExploitRPC

ExploitRPC - open-source Windows-приложение, созданное 2026-02-10.

Назначение:

- отслеживать активность в поддерживаемых Roblox-инжекторах;
- показывать Discord Rich Presence;
- менять статус между idle и Roblox activity.
