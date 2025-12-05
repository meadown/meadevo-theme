# Meadevo Theme

A carefully crafted dark theme for Visual Studio Code, combining Solarized Dark syntax colors with a minimal, distraction-free UI.

## Features

- **Solarized Dark syntax highlighting** - Scientifically designed colors for optimal readability
- **Minimal UI** - Pure black/white/grays with subtle blue accents
- **Eye-friendly** - Designed to reduce eye strain during long coding sessions
- **Focus-oriented** - Clean, distraction-free interface

## Color Palette

### Syntax Colors (Solarized Dark)
- Keywords: Green (#859900)
- Types: Yellow (#b58900)
- Strings: Cyan (#2aa198)
- Numbers: Magenta (#d33682)
- Functions: Blue (#268bd2)
- Comments: Gray (#586e75)
- Constants: Orange (#cb4b16)

### UI Colors
- Editor Background: #1E1E1E
- Sidebar: Matching dark background with black border
- Activity/Status bars: Near-black (#181818)
- Accents: VS Code blue (#007ACC)

## Installation

### From VS Code Marketplace
1. Open VS Code
2. Press `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (Mac)
3. Search for "Meadevo Theme"
4. Click Install
5. Press `Ctrl+K Ctrl+T` and select "Meadevo Dark"

### Manual Installation
1. Copy the `meadevo-theme` folder to `~/.vscode/extensions/`
2. Reload VS Code
3. Press `Ctrl+K Ctrl+T` and select "Meadevo Dark"

## Recommended Settings

For the best experience, add these to your `settings.json`:

```json
{
  "editor.fontFamily": "'SF Mono', 'Monaco', 'Menlo', monospace",
  "editor.fontSize": 13,
  "editor.lineHeight": 1.5,
  "editor.scrollbar.verticalScrollbarSize": 1,
  "editor.scrollbar.horizontalScrollbarSize": 1,
  "workbench.iconTheme": "material-icon-theme",
  "material-icon-theme.folders.theme": "classic",
  "material-icon-theme.folders.color": "#999999",
  "material-icon-theme.opacity": 1
}
```

## Screenshots

[Add screenshots here]

## Contributing

Found a bug or have a suggestion? Please open an issue on [GitHub](https://github.com/yourusername/meadevo-theme).

## License

MIT License - see LICENSE file for details.

## Credits

- Inspired by Solarized Dark by Ethan Schoonover
- UI design focused on developer productivity and wellness
