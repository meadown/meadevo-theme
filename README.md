# Meadevo Theme

```ts
- Created by Dewan Mobashirul (Meadown)
- Copyright (c) 2025 Dewan Mobashirul
- All rights reserved
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dewan%20Mobashirul-blue?style=flat&logo=linkedin)](https://linkedin.com/in/dewan-meadown)
[![GitHub](https://img.shields.io/badge/GitHub-Dewan%20Mobashirul-black?style=flat&logo=github)](https://github.com/meadown)

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

## ⚠️ Highly Recommended Settings

**For the best experience**, Meadevo Theme is designed to work with specific editor settings. While the theme will work without them, these settings are **highly recommended** for the optimal visual experience:

### Quick Setup

Copy all settings from [`recommended-settings.json`](./recommended-settings.json) to your VS Code `settings.json` (File → Preferences → Settings → Open Settings JSON).

### What These Settings Do

- **Icon theme:** Material Icon Theme with classic folders (#999999) - matches the minimal aesthetic
- **Font:** SF Mono (or Monaco/Menlo) - clean, readable monospace font
- **Scrollbar:** Minimal 1px width - reduces visual clutter
- **Font size:** 13px - optimal for readability
- **Line height:** 1.5 - comfortable spacing

**Important:** VS Code themes can only control colors. These editor preferences must be set manually but significantly enhance the Meadevo experience.

### Install Material Icon Theme

```bash
# Press Ctrl+P in VS Code and paste:
ext install PKief.material-icon-theme
```

## Screenshots

[Add screenshots here]

## Contributing

Found a bug or have a suggestion? Please open an issue on [GitHub](https://github.com/meadown/meadevo-theme).

## License

MIT License - see LICENSE file for details.

## Credits

- Inspired by Solarized Dark by Ethan Schoonover
- UI design focused on developer productivity and wellness
