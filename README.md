# Organizr Custom Plugin Marketplace

This repository provides a **custom plugin marketplace source for Organizr**.

Plugins listed here can be installed directly through the Organizr plugin marketplace without any manual file copying.

---

## How to Add This Marketplace

Open Organizr and go to:

```
Settings → Plugins → Settings → Marketplace
```

In **External Marketplace Repo**, add:

```
https://github.com/Katsugami/Organizr-Plugins
```

Save, then open **Plugins → Marketplace**. The plugins from this repository will appear and can be installed in one click.

---

## Available Plugins

### wizarrInvite `v2.0.0`

> Generate and manage Wizarr invitation links directly from Organizr.

**Key features:**

- **Automatic Slots** — multiple independent invitation channels, each with its own permanent URL (`/display/1`, `/display/2`…), user limit, and settings
- **Manual invitation creation** from the settings panel
- Automatic invite validation and recreation when settings change
- Per-slot user limit enforcement
- Server and library selection
- Bundle support (positional index: `1` = first bundle, `2` = second…)
- Multi-language public display pages (English, French, Spanish)
- **Debug log viewer** — view and clear plugin activity logs from the UI
- **Wizarr API Docs** quick-access links (internal + external)
- Optimized HTTP requests with connection timeout to prevent Wizarr from freezing when a Plex server is unreachable

**Tested with:** Organizr 2.1.4010 — Wizarr v2026.4.0

**Repository:** https://github.com/Katsugami/wizarrInvite

---

## Authors

Katsugami

AI development assistance: ChatGPT (v1.0) — Claude by Anthropic (v2.0)

Plugin code developed with the assistance of ChatGPT then Claude, with integration, testing, and assembly by Katsugami.
