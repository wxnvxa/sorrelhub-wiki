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
- `3` - NextGen era

Generation should not change for every redesign. It should mean a real new era.

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

## Rule

Do not call every new button a `Major` release.

- changed a button - patch;
- added a page - minor;
- changed auth/API in a breaking way - major;
- changed the whole product era - generation.
