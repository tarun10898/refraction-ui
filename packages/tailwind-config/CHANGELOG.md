# @refraction-ui/tailwind-config

## 0.1.4

### Patch Changes

- 83cf3d8: fix: resolve core styling, layout, and typography bugs

  - Fixed `app-shell`, `auth-shell`, and `page-shell` factories where `undefined` config values incorrectly overwrote default settings.
  - Added `@tailwindcss/typography` plugin to the `refractionPreset` to ensure proper markdown styling.
  - Upgraded the documentation site's code blocks to use `shiki` for proper syntax highlighting.

## 0.1.3

### Patch Changes

- dabcbd6: chore: force release to update latest npm tags

## 0.1.2

### Patch Changes

- c083c7d: docs: update readme to reflect supported and planned frameworks and trigger a final release test

## 0.1.1

### Patch Changes

- 30d38ee: chore: test new changesets + oidc release workflow
