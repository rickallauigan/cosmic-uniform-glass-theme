# Uniform Glass Dark Theme for COSMIC™ Desktop

A beautiful, modern dark theme for the COSMIC™ Desktop featuring a sleek glass design with smooth, uniform rounded corners and translucent backgrounds.

## Features

- **Glass Design**: Uniform Translucent backgrounds
- **Uniform Rounded Corners**: Consistent 12px radius across all UI elements
- **Optimized Dark Palette**: Carefully crafted neutral grays with vibrant accent colors
- **Modern Color Scheme**: Rich blues, purples, pinks, and warm tones
- **Clean Typography**: Optimized spacing and layout for readability

## Screenshots

### Applications 
![Apps View](images/apps.png)

### Launcher
![Launcher](images/launcher.png)

### Workspace Overview
![Workspace](images/workspace.png)

### Tiled Windows
![Tiled Layout](images/tiled.png)

### Windowed Mode
![Windowed Mode](images/windowed.png)

### Applet Panel
![Applet](images/applet.png)

## Theme Variants

### Uniform Glass Dark

The original glass-focused theme. It keeps `is_frosted: true` so it can use compositor blur when COSMIC gains full frosted-glass support.

### Uniform Glass Dark Performance

A performance-first variant with the same palette, spacing, rounded corners, transparency, and overall visual design, but with compositor frosted blur explicitly disabled.

This variant is intended for users who want the Uniform Glass appearance without enabling additional blur rendering when COSMIC compositor support becomes available.

- Same dark palette
- Same macOS-inspired blue accent
- Same rounded geometry
- Same window gaps
- Same translucent background
- Frosted compositor blur disabled
- No extra daemon or background process

## Installation

1. Open COSMIC™ Settings > Appearance
2. Select Import

## Theme Details

- **Base Style**: Dark theme with frosted glass effect
- **Background Opacity**: 40% transparency for main backgrounds
- **Accent Color**: Vibrant blue (#0A84FF)
- **Corner Radius**: Uniform 12px rounded corners
- **Window Gaps**: 3px inner, 8px outer

> **⚠️ Note on Frosted Glass Effect**: The backdrop blur effect (frosted glass) requires compositor-level blur support in cosmic-comp, which is currently planned for COSMIC Epoch 2. Currently, you'll see transparency without the backdrop blur. This theme is future-ready with `is_frosted: true` enabled and will automatically gain the full frosted glass blur effect once it's implemented in the compositor.
>
> **References**:
> - [cosmic-comp Issue #511 - Blur/Frosted Glass support](https://github.com/pop-os/cosmic-comp/issues/511)
> - [cosmic-epoch Issue #604 - Blur options for transparencies](https://github.com/pop-os/cosmic-epoch/issues/604)

## Color Palette

The theme includes a comprehensive color palette with:
- 11 neutral gray shades (from pure black to pure white)
- 8 vibrant accent colors (blue, indigo, purple, pink, red, orange, yellow, green)
- Extended colors for additional UI elements
- Success, warning, and destructive state colors

## License

This theme is licensed under the Mozilla Public License 2.0 (MPL-2.0). See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.


## Acknowledgments

- Created for the [COSMIC™ Desktop](https://github.com/pop-os/cosmic-epoch) environment by System76
- Inspired by modern glass-morphism design trends

---


If you enjoy this theme, please consider giving it a star!
