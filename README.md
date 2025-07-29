# Shadow Discord Theme

A dark, transparent Discord theme inspired by Solo Leveling's Sung Jin-Woo with dramatic red/orange accents.

![Shadow Theme Preview](https://raw.githubusercontent.com/SallahBoussettah/Shadow/main/assets/images/Sung-jin.png)

## Features

- **🌟 Transparent UI Elements** - All Discord components have transparency with backdrop blur effects
- **🎨 Custom Background** - Features the iconic Sung Jin-Woo wallpaper from Solo Leveling
- **🔥 Red/Orange Accent Colors** - Inspired by the dramatic sky colors in the wallpaper
- **📖 Enhanced Text Readability** - Text shadows and optimized colors for better visibility
- **🏠 Custom Home Icon** - Shadow-themed home button icon
- **⚡ Cross-Platform Support** - Works with both BetterDiscord and Vencord
- **🛠️ Professional Build System** - Based on ClearVision's proven architecture

## Installation

### BetterDiscord
1. Download `Shadow.theme.css` from the [releases page](https://github.com/SallahBoussettah/Shadow/releases)
2. Place it in your BetterDiscord themes folder:
   - **Windows**: `%appdata%\betterdiscord\themes`
   - **macOS**: `~/Library/Application Support/betterdiscord/themes`
   - **Linux**: `~/.config/betterdiscord/themes`
3. Enable the theme in Discord Settings > Themes

### Vencord
1. Download `Shadow.theme.css` from the [releases page](https://github.com/SallahBoussettah/Shadow/releases)
2. Place it in your Vencord themes folder:
   - **Windows**: `%appdata%\vencord\themes`
   - **macOS**: `~/Library/Application Support/vencord/themes`
   - **Linux**: `~/.config/vencord/themes`
3. Enable the theme in Discord Settings > Vencord > Themes

### Online Installation
You can also use the theme online by adding this CSS import:
```css
@import url("https://raw.githubusercontent.com/SallahBoussettah/Shadow/main/Shadow.theme.css");
```

## Color Palette

The theme uses colors extracted from the Sung Jin-Woo wallpaper:

- **Main Accent**: `#ff4757` (vibrant red from the dramatic sky)
- **Hover Color**: `#ff3742` (deeper red for interactions)
- **Warning**: `#ffa502` (orange tones from the sunset)
- **Success**: `#2ed573` (contrasting green for positive actions)
- **Background Transparency**: 85% (adjustable)

## Customization

You can customize the theme by modifying these CSS variables in your custom CSS:

```css
:root {
  /* Accent Colors */
  --main-color: #ff4757; /* Main red accent */
  --hover-color: #ff3742; /* Hover state color */
  --success-color: #2ed573; /* Success/positive actions */
  --danger-color: #ff4757; /* Danger/negative actions */
  --warning-color: #ffa502; /* Warning color */
  
  /* Background Settings */
  --background-shading-percent: 85%; /* Transparency level (0-100%) */
  --background-filter: brightness(0.8) contrast(1.1) saturate(1.2); /* Image filters */
  
  /* Status Colors */
  --online-color: #2ed573;
  --idle-color: #ffa502;
  --dnd-color: #ff4757;
  --streaming-color: #a55eea;
  --offline-color: #747d8c;
}
```

## Building from Source

To build the theme from source:

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Build the Theme**:
   ```bash
   npm run build
   ```

3. **Development Build** (for testing):
   ```bash
   npm run test
   ```

### Build Requirements

- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) or [pnpm](https://pnpm.io/)
- [Sass](https://sass-lang.com/)
- [PostCSS](https://postcss.org/) with Autoprefixer

## File Structure

```
Shadow/
├── src/                      # Source SCSS files
│   ├── backend/             # Core functionality and class definitions
│   ├── theme/               # Theme components
│   │   ├── app/            # App-wide styling
│   │   ├── chat/           # Chat area styling
│   │   ├── sidebar/        # Sidebar styling
│   │   └── ...             # Other components
│   ├── main.scss           # Main theme entry point
│   └── start/              # Theme metadata
├── assets/
│   ├── images/
│   │   └── Sung-jin.png    # Background wallpaper
│   └── icons/
│       └── shadow-home.svg # Custom home icon
├── public/                  # Built CSS files
├── dist/                   # Distribution files
└── Shadow.theme.css        # Main theme file for users
```

## Theme Variants

The Shadow theme supports all Discord theme modes:

- **Light Mode**: High contrast with bright overlays
- **Dark Mode**: Balanced transparency (default)
- **Darker Mode**: Increased transparency for dramatic effect
- **Midnight Mode**: Maximum transparency for immersive experience

## Credits

- **Theme Author**: [SallahBoussettah](https://github.com/SallahBoussettah)
- **Wallpaper**: Solo Leveling - Sung Jin-Woo artwork
- **Architecture**: Based on [ClearVision](https://github.com/ClearVision/ClearVision-v7) theme structure
- **Version**: 1.0.0

## Support

If you encounter any issues or have suggestions:

1. Check the [Issues](https://github.com/SallahBoussettah/Shadow/issues) page
2. Create a new issue with detailed information
3. Join our [Discord server](https://discord.gg/dHaSxn3) for community support

## License

This theme is released under the MIT License. Feel free to modify and distribute as needed.

---

**Made with ❤️ by SallahBoussettah**