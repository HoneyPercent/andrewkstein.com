# Brit Mitzvah Page — Project Conventions

Project-specific rules for `andrewkstein.com/preview/brit-mitzvah/` (eventual home: `tish.life/brit-mitzvah`).

## Hyperlinks

**All `<a href="https://...">` external links open in a new tab.** When adding or editing any hyperlink in `index.html`, include `target="_blank" rel="noopener"`.

Applies to: nav, body, FAQ, footer — anything pointing off-page. Skip for in-page anchors (`#section`), mailto, and tel.

Origin: Karen Shacham's feedback 2026-05-19. She wants every off-page click to preserve the user's place on the Tish page.

## Source of truth

The markdown draft lives in the Obsidian vault at `Personal/Tish/Brit Mitzvah Program Page - DRAFT.md`. When changing copy on the HTML page, mirror the change in the markdown so the two stay in sync.
