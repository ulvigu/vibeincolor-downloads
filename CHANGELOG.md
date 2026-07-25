# Changelog

## 0.2.0 — 2026-07-25

**Your vibe, your palette.**

### Features

- Create dark or light themes inside any vibe with readable starting palettes.
- Edit exact background, foreground, and accent hex values, or tune any color with the built-in picker.
- Rename custom themes, edit their palettes, and delete them directly from the theme row.
- Restore custom themes, the selected theme, and its vibe across app launches.

## 0.1.1 — 2026-07-22

**Reliable code-font search.**

### Fixes

- Update code-font results immediately after clearing the interface-font search and switching typography targets.

## 0.1.0 — 2026-07-22

**Themes for ChatGPT on macOS.**

### Release scope

- Bundle 200 original Vibe in Color themes: twenty carefully differentiated palettes for each of ten work vibes, split evenly between dark and light appearances.
- Give every theme a hand-curated name that combines a sensory part of its vibe with a playful AI or machine-learning concept.
- Search themes by name, vibe, or palette family and filter the light and dark libraries.
- Show a representative ChatGPT-style preview for prose, code, diffs, and message surfaces without claiming pixel-identical rendering across every ChatGPT surface.
- Configure exact interface and code font faces and independent preview sizes, with system-font fallback when a saved face is unavailable.
- Copy a complete `codex-theme-v1` value from an IP-neutral clipboard icon and confirm: “Copied. Open ChatGPT → Settings → Appearance → Import.”

### Distribution and quality

- Target macOS 14 and Apple Silicon with arm64-only development, validation, CI, and release packaging.
- Classify Vibe in Color as a Utilities app and include descriptor and copyright metadata in the About panel.
- Add native keyboard paths for search, theme selection, typography, and clipboard export.
- Test clipboard-write failure and unavailable-font fallback behavior.
- Keep ChatGPT as descriptive compatibility language and retain the unofficial-app disclaimer.
