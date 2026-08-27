---
title: Продукты
---

# Продукты

## Sorrel Hub

Главный бренд и зонтик для всей экосистемы.

Исторически Sorrel Hub начался как Discord-сервер для Roblox-игры `Щавель обби` и будущих плейсов Winner. Это важная деталь, потому что старый Sorrel Hub был не про script hub в нынешнем смысле. Он был больше про комьюнити вокруг игры и будущих Roblox-проектов.

Позже, примерно в сентябре-октябре 2025, Sorrel Hub начал превращаться в проект под Roblox scripts, web, backend/API и другие dev-направления.

Направления:

- web
- backend/API
- Luau / Roblox scripts
- UI/UX
- AI tools
- desktop/tools experiments

## Sorrel Hub после 2026-06-16

Текущий этап Sorrel Hub начинается после `2026-06-16 16:00 UTC+5`.

Winner и Lovey0x остаются владельцами и финальным направлением Sorrel Hub. Lox / `lox_228` относится к pre-NextGen эпохе как co-owner старого Sorrel Hub до конца той эпохи, но не был создателем ни старого, ни текущего Sorrel Hub.

`NextGen` лучше понимать как название предыдущего chapter/reboot. После точки перезапуска новые Discord-серверы, сайт и версии ведутся как новая линейка Sorrel Hub.

## WinWare

WinWare - Roblox/Luau направление с фокусом на HvH, Visuals и связанные модули.

Если объяснять проще, WinWare не стоит описывать только как farming script. У него была PVE-история, но текущий смысл направления шире: визуалы, HvH-логика, gameplay modules, UI и Roblox/Luau эксперименты.

Известные этапы:

- `WinWare:PVE` - первая версия, создана 2025-11-23.
- `WinWare Pre-Alpha Test` - объявлен 2025-12-31 и снова открыт 2026-01-01.

`WinWare:PVE` был farming script для `Build A Boat For Treasure`, использовал `Luna UI`, имел key system и сейчас discontinued.

## LoveyWare

LoveyWare - направление Lovey0x, а не просто "один скрипт".

Если WinWare описывать через HvH/Visuals, то LoveyWare лучше описывать как bypass-oriented направление и набор модулей вокруг этого подхода. Это часть текущей истории Sorrel Hub, потому что Lovey0x является co-owner Sorrel Hub, а не просто автором отдельного файла.

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
- статус: partially discontinued
- связан с Roblox gameplay modifications и script analysis
- ранние тесты predict tp стали частью истории знакомства Winner и Lovey0x

## SHProtect AntiCheat

SHProtect AntiCheat - отдельное Roblox-направление Sorrel Hub для защиты игровых серверов от подозрительного движения, злоупотребления RemoteEvent и части клиентских вмешательств.

Проект построен вокруг серверной проверки. В него входят детекторы скорости, телепорта, fly/hover, infinite jump, noclip, fling, CFrame-движения и remote spam. Клиентский watchdog отправляет heartbeat и ограниченные отчеты о состоянии, но не является самостоятельной границей безопасности.

Пороговые значения и реакция на нарушения вынесены в конфигурацию. Для легитимных телепортов, dash, knockback и scripted motion предусмотрены exemption tags, чтобы игровые механики не конфликтовали с проверками.

Исходный код опубликован в репозитории [`sorrelhub/shprotect-ac`](https://github.com/sorrelhub/shprotect-ac). Это инфраструктурный Roblox-проект, а не пользовательский script hub.

## Forum

Forum - discontinued.

## ExploitRPC

ExploitRPC - discontinued.
