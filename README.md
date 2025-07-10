# 🚀 Retro-Futuristic Obsidian Theme

An 80's cyberpunk-inspired theme for Obsidian, perfect for TTRPG campaigns and sci-fi content.

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

## 📁 File Structure

```
styles.css          # Main orchestrator file
├── variables.css   # Base layer: colors, fonts, variables
├── typography.css  # Typography layer: headings and text
├── layout.css      # Layout layer: base compatibility
├── blockquotes.css # Layout layer: quote styling
├── lists.css       # Layout layer: list formatting
├── tables.css      # Layout layer: table styling
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
4. **Components**: Complex UI elements (callouts)
5. **Utilities**: Override classes and special effects

## 🚀 Installation

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

---

*Transform your Obsidian vault into a cyberpunk command center! 🎯*
