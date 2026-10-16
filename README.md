# Notecards

A simple notecard editor that saves your notes as plain Markdown files in a folder on your computer. No account, no server, no sync service. It's one HTML file.

**Use it:** open the GitHub Pages link for this repo in Chrome, Edge, or Brave, or download `index.html` and open it directly.

## What it does

- Pick a folder; every note is saved there as `Title.md`.
- Light formatting: bold, italic, headings, bullet lists, inline code.
- Link notes with `[[Note Title]]` (type `[[` or press Ctrl+K). Renaming a note updates links to it.
- Preview mode (Ctrl+E) shows formatting and makes links clickable.
- Autosaves as you type, remembers your folder, and picks up changes made to the files elsewhere.

That's it, on purpose.

## Privacy

Your notes never leave your computer. The page runs entirely in your browser and reads and writes only the folder you choose. Hosting the page on GitHub Pages doesn't send your notes anywhere.

## Browser support

Chrome, Edge, Brave, and other Chromium browsers. Firefox and Safari don't support writing to local folders from a web page.

## Keyboard shortcuts

| Keys | Action |
|---|---|
| Ctrl/Cmd+B | Bold |
| Ctrl/Cmd+I | Italic |
| Ctrl/Cmd+K | Link to a note |
| Ctrl/Cmd+E | Toggle preview |
| Ctrl/Cmd+S | Save now |
| Alt+N | New note |

## License

Copyright © 2026 G. Michael Rapp. Released under the [GNU Affero General Public License v3.0](LICENSE).
