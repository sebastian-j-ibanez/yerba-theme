# Yerba 🧉

A warm, low-contrast dark theme with earthy tones.

<img src="docs/resources/helix-rs.png" alt="Rust snippet in yerba theme" />

## Palette

| Color | Hex | Preview |
|---|---|---|
| Moss | `#6a9a6a` | ![moss](https://img.shields.io/badge/moss-%236a9a6a?style=flat-square&color=6a9a6a) |
| Terracotta | `#a05a4a` | ![terracotta](https://img.shields.io/badge/terracotta-%23a05a4a?style=flat-square&color=a05a4a) |
| Sand | `#a89880` | ![sand](https://img.shields.io/badge/sand-%23a89880?style=flat-square&color=a89880) |
| Copper | `#b87848` | ![copper](https://img.shields.io/badge/copper-%23b87848?style=flat-square&color=b87848) |
| Flint | `#909088` | ![flint](https://img.shields.io/badge/flint-%23909088?style=flat-square&color=909088) |
| Background | `#181818` | ![bg](https://img.shields.io/badge/bg-%23181818?style=flat-square&color=181818) |
| Foreground | `#bcbcbc` | ![fg](https://img.shields.io/badge/fg-%23bcbcbc?style=flat-square&color=bcbcbc) |

## Ports

- [Helix](helix/)
- [Ghostty](ghostty/)
- [VS Code](vscode/)
- [Neovim](https://github.com/yerba-theme/nvim)

## Install

### Helix, Ghostty

```sh
git clone https://github.com/your-user/yerba-theme
cd yerba-theme

# install for a specific app
./install.sh helix
./install.sh ghostty

# or install all
./install.sh all
```

### VS Code

Install the [Yerba](https://marketplace.visualstudio.com/items?itemName=sebastian-j-ibanez.yerba-theme) extension by sebastian-j-ibanez from the extension page.

Alternatively open VS Code, launch quick open (Ctrl+P), paste the following command, and press enter:

```
ext install sebastian-j-ibanez.yerba-theme
```

### Neovim

Add to your lazy.nvim config:

```lua
{ "yerba-theme/nvim", config = function() vim.cmd.colorscheme("yerba") end }
```

Or install manually with `:packadd`:

```sh
git clone https://github.com/yerba-theme/nvim ~/.local/share/nvim/site/pack/themes/start/yerba
```

Then add `vim.cmd.colorscheme("yerba")` to your config.

## License

[MIT](LICENSE)
