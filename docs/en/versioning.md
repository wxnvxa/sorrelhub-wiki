# Versioning

Planned scheme:

```txt
Generation.Major.Minor.Patch-Release
```

Short form:

```txt
G.M.m.p-release
```

## Generation

A major era of the project.

Examples:

- `1` - old Sorrel Hub
- `2` - v2 / redesign era
- `3` - previous NextGen era

Generation should not change for every redesign. It should mean a real new era.

## 2026-06-16 Reset

After `2026-06-16 16:00 UTC+5`, Sorrel Hub versions start again as a new line.

Do not mix versions from the previous NextGen era with versions after this reset. Old versions remain historical and can still be referenced as old NextGen-era versions, but they are not part of the new Sorrel Hub line.

This document does not assign a concrete new version number because the current docs do not provide one. The rule is the important part: post-reset versions are a fresh sequence, and old NextGen numbers stay in the previous sequence.

## Major

Large changes that break compatibility or strongly change the product.

Examples:

- new auth system;
- new loader protocol;
- large dashboard/auth architecture change;
- old API contract removal.

## Minor

New features without heavy breaking changes.

Examples:

- Connected services;
- new product page;
- new profile settings;
- new modules.

## Patch

Fixes, security updates, and small improvements.

Examples:

- UI bugfix;
- CSP fix;
- loader bugfix;
- OAuth redirect fix.

## Release

State label.

Options:

- `dev`
- `pre-alpha`
- `alpha`
- `beta`
- `rc.1`
- `stable`
- `hotfix`

## Examples

```txt
3.0.0.0-pre-alpha
3.1.0.0-alpha
3.1.2.0-beta
3.1.2.1-hotfix
3.2.0.0-stable
```

These are examples from the old generation-style scheme, not assigned post-reset versions.

## Rule

Do not call every new button a `Major` release.

- changed a button - patch;
- added a page - minor;
- changed auth/API in a breaking way - major;
- changed the whole product era - generation.
