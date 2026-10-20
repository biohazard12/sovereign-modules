# Sovereign Modules

Curated module catalog for the **Sovereign** Android toolkit by Sovereign Labs.

The Sovereign app's Module Store reads `repo.json` from this repo:

```
https://raw.githubusercontent.com/biohazard12/sovereign-modules/main/repo.json
```

## Format

`repo.json` holds a `modules` array. Each entry:

- `id` — module id (matches the module's own id)
- `name`, `version`, `author`, `description`
- `icon_url` — optional icon (null allowed)
- `zip_url` — direct download link to the module zip

Only hand-picked, curated modules are listed here. Sovereign's own modules are published through this repo's Releases.
