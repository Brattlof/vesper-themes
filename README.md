# Vesper Themes

A collection of dark themes for VS Code — each with its own personality.

## Themes

### Vesper Dusk
A minimal, muted dark theme with warm earthy tones. Sage greens, sandy beiges, and stone grays — like a quiet landscape at twilight.

### Vesper Ember
A bolder dark theme with vivid reds, warm oranges, soft yellows, and greens — like embers glowing against the dark.

## Installation

1. Clone or download this repository
2. Copy the folder to your VS Code extensions directory:
   - **Windows:** `%USERPROFILE%\.vscode\extensions\`
   - **macOS:** `~/.vscode/extensions/`
   - **Linux:** `~/.vscode/extensions/`
3. Restart VS Code
4. Open **Preferences: Color Theme** and select **Vesper Dusk** or **Vesper Ember**

## Recommended Font

These themes pair well with [Monaspace Neon](https://github.com/githubnext/monaspace) — a monospaced font by GitHub with a clean, modern look.

**Download Monaspace Neon:**
- [GitHub Releases](https://github.com/githubnext/monaspace/releases)
- [monaspace.githubnext.com](https://monaspace.githubnext.com/)

After installing the font, add these to your VS Code `settings.json`:

```json
{
  "editor.fontFamily": "Monaspace Neon",
  "editor.fontLigatures": false
}
```

Setting `fontLigatures` to `false` keeps characters like `=>`, `!=`, and `<=` displayed as separate symbols instead of combined glyphs.
