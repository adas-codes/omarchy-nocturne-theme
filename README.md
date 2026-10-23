# Nocturne — Omarchy Theme

A dark, cinematic Omarchy theme built around charcoal backgrounds, warm ivory text, ember accents, moss green, smoke blue, and dusty plum.

## Install

```bash
omarchy-theme-install https://github.com/YOUR_GITHUB_USERNAME/omarchy-nocturne-theme.git
```

Replace `YOUR_GITHUB_USERNAME` with your GitHub username. Then select **Nocturne** from the Omarchy theme selector.

## Contents

- `colors.toml` — Omarchy semantic palette
- `backgrounds/` — wallpaper collection
- `preview.jpg` — theme preview
- `icons.theme` — icon theme selection
- Terminal palettes for Kitty, Alacritty, and Ghostty
- Optional styling for Hyprland, Hyprlock, Mako, Waybar, Walker, SwayOSD, and btop
- `chromium.theme` — Chromium theme color triplet

## Notes

- This repository is based on an Aether-generated Omarchy theme and includes additional application configuration files.
- App-specific config support can vary with Omarchy and application versions. Test locally before publishing a release.
- `neovim.lua` does not install or force a third-party colorscheme. `vscode.json` is a placeholder for an optional VS Code extension integration; configure it for a real extension before relying on it.
- Wallpapers are supplied in `backgrounds/`; wallpaper cycling and theme menu behavior depend on your Omarchy version.
- The icon theme is set to `Yaru-purple` from the Aether export. Change `icons.theme` if you prefer another installed icon theme.

## Credits

Palette and wallpapers: theme author. Omarchy is maintained by [Basecamp](https://github.com/basecamp/omarchy).
