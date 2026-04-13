<!-- Parent: ../AGENTS.md -->
<!-- Generated: 2026-03-19 | Updated: 2026-03-19 -->

# fonts

## Purpose

Font resource directory containing TrueType and webfont files used in HTML reports.

## Key Files

| File | Description |
|------|-------------|
| `truetype/*.ttf` | TrueType font files for desktop rendering |
| `webfonts/*.woff`, `*.woff2` | Web-optimized font subsets |

## Subdirectories

| Directory | Purpose |
|-----------|---------|
| `truetype/` | Desktop TrueType fonts |
| `webfonts/` | Web-optimized fonts with subsets |

## For AI Agents

### Working In This Directory

- **Read-only**: Fonts are assets, not source code
- Do not modify font files
- Reference fonts in HTML reports using relative paths

### Testing Requirements

- Verify font loading in browser
- Check fallback fonts are specified

## Dependencies

### Internal

- Root HTML reports consume these fonts

### External

- Font files from original font vendors

<!-- MANUAL: -->
