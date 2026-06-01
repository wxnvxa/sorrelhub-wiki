# Версионирование

Планируемая схема:

```txt
Generation.Major.Minor.Patch-Release
```

Коротко:

```txt
G.M.m.p-release
```

## Generation

Большая эпоха проекта.

Примеры:

- `1` - старый Sorrel Hub
- `2` - v2 / redesign era
- `3` - NextGen era

Generation не нужно менять ради каждого redesign. Это должна быть новая эпоха проекта.

## Major

Крупные изменения, которые ломают совместимость или сильно меняют продукт.

Примеры:

- новая auth-система;
- новый loader protocol;
- перенос cabinet на subdomain;
- отказ от старого API контракта.

## Minor

Новые функции без грубого ломания.

Примеры:

- Connected services;
- новая страница продукта;
- новые настройки профиля;
- новые модули.

## Patch

Фиксы, безопасность и мелкие улучшения.

Примеры:

- UI bugfix;
- CSP fix;
- loader bugfix;
- OAuth redirect fix.

## Release

Метка состояния.

Варианты:

- `dev`
- `pre-alpha`
- `alpha`
- `beta`
- `rc.1`
- `stable`
- `hotfix`

## Примеры

```txt
3.0.0.0-pre-alpha
3.1.0.0-alpha
3.1.2.0-beta
3.1.2.1-hotfix
3.2.0.0-stable
```

## Правило

Не нужно называть каждую новую кнопку `Major`.

- поменял кнопку - patch;
- добавил страницу - minor;
- поменял auth/API так, что старое поведение ломается - major;
- сменил всю эпоху продукта - generation.
