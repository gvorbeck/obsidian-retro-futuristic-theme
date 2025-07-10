# 🚀 Retro-Futuristic Obsidian Theme

![Theme Preview](https://img.shields.io/badge/Theme-Retro--Futuristic-yellow?style=for-the-badge)
![CSS](https://img.shields.io/badge/CSS-Layers-blue?style=for-the-badge)
![Obsidian](https://img.shields.io/badge/Obsidian-Compatible-purple?style=for-the-badge)

An 80's cyberpunk-inspired theme for Obsidian, perfect for TTRPG campaigns and sci-fi content.

> ⚡ **Transform your Obsidian vault into a cyberpunk command center!** ⚡

## 📸 Preview

_Coming soon - screenshots of the theme in action_

## ✨ Features

### 🎨 Visual Design

- **Retro-futuristic aesthetic** with cyberpunk elements
- **VT323 monospace font** for authentic computer terminal feel
- **Yellow primary color** (`#e8d8a3`) with neon accent colors
- **Block character decorations** (▓▒░) throughout the interface
- **Gradient borders and glowing effects**

### 🔧 Technical Excellence

- **Cross-view compatibility** - Works in both reading and edit modes
- **CSS Layers architecture** for maintainable and organized code
- **Performance optimized** animations and effects
- **Zero CSS errors** - Fully validated

### 📦 Component Library

#### Headings (H1-H6)

- **Hierarchical block character prefixes**: `▓▒░`, `▒░`, `░`, `▸`, `◦`, `·`
- **Gradient underlines** for H1 and H2
- **Interactive hover effects** with pulsing animations
- **Cross-view compatibility** for edit mode

#### Callouts

- **Tech panel aesthetics** with gradient borders
- **Multiple animation layers**: scanlines, data streams, status indicators
- **Type-specific styling** for warnings and errors
- **Enhanced hover states** with glow effects

#### Tables

- **Corner bracket indicators** (`┌`, `┘`)
- **Tech-style headers** with block character prefixes
- **Hover effects** and gradient backgrounds
- **Retro-futuristic border styling**

#### Blockquotes

- **Tech accent arrows** (`▸▸`)
- **Gradient backgrounds** with yellow accent borders
- **Subtle grid pattern overlays**
- **Edit mode compatibility**

#### Lists

- **Decimal leading zero** formatting (01, 02, 03...)
- **Monospace font** for list markers
- **Consistent spacing** and alignment

#### Links

- **Dithering fade effects** on hover with pixelated patterns
- **Scanline animations** for focus states
- **Type-specific indicators**: `▸` for external, `◦` for internal
- **Special styling** for wiki-links, tags, and broken links
- **Contextual appearance** within different components

## 📁 File Structure

```
styles.css          # Main orchestrator file
├── variables.css   # Base layer: colors, fonts, variables
├── typography.css  # Typography layer: headings and text
├── blockquotes.css # Layout layer: quote styling
├── lists.css       # Layout layer: list formatting
├── tables.css      # Layout layer: table styling
├── links.css       # Components layer: link styling with dithering
├── callouts.css    # Components layer: callout panels
└── utilities.css   # Utilities layer: helper classes
```

## 🎯 CSS Layers Architecture

```css
@layer base, typography, layout, components, utilities;
```

1. **Base**: Variables, fonts, and foundational styles
2. **Typography**: Heading styles and text formatting
3. **Layout**: Structural elements (lists, tables, quotes)
4. **Components**: Complex UI elements (callouts, links)
5. **Utilities**: Override classes and special effects

## 🚀 Quick Start

### Installation

1. **Download**: Clone or download this repository
2. **Copy**: Place all `.css` files in your vault's `.obsidian/snippets/` folder
3. **Enable**: Go to Obsidian Settings → Appearance → CSS snippets
4. **Activate**: Toggle on the "styles" snippet

### Clone with Git

```bash
# Clone the repository
git clone https://github.com/yourusername/obsidian-retro-futuristic-theme.git

# Copy files to your vault
cp obsidian-retro-futuristic-theme/*.css /path/to/your/vault/.obsidian/snippets/
```

## 🔧 Requirements

- **Obsidian** v0.15.0 or later
- **Internet connection** for VT323 font (auto-loaded)
- **Modern browser** with CSS layers support

1. Copy all CSS files to your Obsidian vault's `.obsidian/snippets/` folder
2. Enable CSS snippets in Obsidian Settings → Appearance → CSS snippets
3. Toggle on the "styles" snippet

## 🎨 Color Palette

- **Primary**: `#e8d8a3` (Yellow) - Main accent color
- **Blue**: `#6b8ca4` - Info callouts, links
- **Green**: `#7a8f71` - Success callouts, tips
- **Orange**: `#c28c5c` - Warning callouts
- **Red**: `#b06c5a` - Error callouts, external links
- **Purple**: `#9c7a99` - Example callouts
- **Gray**: `#a8a8a8` - Quote callouts

## 🔧 Utility Classes

- `.retro-glow` - Instant cyberpunk text glow
- `.tech-border` - Gradient tech panel borders
- `.cyber-text` - Monospace uppercase styling
- `.block-accent` - Add block character prefixes
- `.scan-effect` - Animated scanning line effect

## 📝 Usage Notes

- Works best with **VT323 font** (automatically imported)
- Optimized for **TTRPG content** and sci-fi themes
- All animations are **performance optimized**
- **Cross-browser compatible** with modern CSS features

## 🔄 Version History

- **v1.0** - Initial retro-futuristic theme with full component library
- Complete cross-view compatibility
- CSS layers architecture implementation
- Comprehensive documentation

## 🎯 Perfect For

- 📖 TTRPG campaign notes and worldbuilding
- 🚀 Sci-fi writing and research
- 💻 Technical documentation
- 🎮 Gaming content organization
- 🌌 Cyberpunk-themed projects

## 🤝 Contributing

Contributions are welcome! Please feel free to:

- 🐛 Report bugs
- 💡 Suggest new features
- 🔧 Submit pull requests
- ⭐ Star the repository if you find it useful

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by 80's cyberpunk aesthetics
- Built for the amazing Obsidian community
- Uses Google Fonts VT323 for authentic retro feel

## 📧 Support

- **Issues**: [GitHub Issues](https://github.com/yourusername/obsidian-retro-futuristic-theme/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/obsidian-retro-futuristic-theme/discussions)

---

_Transform your Obsidian vault into a cyberpunk command center! 🎯_

**Made with 💚 for the Obsidian community**
