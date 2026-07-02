# Hyprdots 🌙

A minimalist, industrial, and grayscale Hyprland configuration designed for high precision and seamless workflow. This setup leverages a modular Lua-based configuration system to maintain a clean separation between core variables, window rules, and keybindings.

## ✨ Features
- **Modular Lua Config**: Easy to maintain and extend through categorized configuration files.
- **Noctalia Integration**: Deeply integrated with Noctalia for a cohesive system UI and control center.
- **Aria AI Integration**: Dedicated workspace and triggers for the Aria AI assistant.
- **Precision Workflow**: Optimized for research and data science with built-in OCR and lens utilities.

## 🛠️ Core Dependencies

To get this setup running, you will need the following packages installed on your system:

### System Tools
- `hyprland` - The Wayland compositor.
- `noctalia` - System UI, panel, and control center.
- `snappy-switcher` - Advanced window/workspace switching.

### Utilities
- `playerctl` - Media playback control.
- `wpctl` - Audio management (WirePlumber).
- `grimblast` - Screenshot utility.
- `tesseract` - OCR engine (used by `hypr-ocr`).
- `wl-clipboard` - Wayland clipboard management.

## 🚀 Installation

The recommended way to install this configuration is by cloning the repository and symlinking the folders to your `.config` directory. This allows you to update the setup easily via `git pull`.

```bash
# Clone the repository
git clone https://github.com/axioncs/hyprdots.git ~/.local/share/hyprdots

# Backup existing config (if any)
mv ~/.config/hypr ~/.config/hypr.bak

# Symlink the configuration
ln -s ~/.local/share/hyprdots/hypr ~/.config/hypr
```

## 🔄 Updating

To pull the latest changes from the repository:

```bash
cd ~/.local/share/hyprdots
git pull
```

## ⌨️ Keybindings

### 🚀 Applications & System
| Keybind | Action |
| :--- | :--- |
| `SUPER + T` | Terminal |
| `SUPER + E` | File Manager |
| `SUPER + W` | Browser |
| `SUPER + C` | Editor |
| `SUPER + A` | Twintail Launcher |
| `CTRL + SUPER + A` | Hypr-Lens |
| `CTRL + SUPER + Z` | Hypr-OCR |
| `SUPER + Space` | Toggle Aria AI Workspace |
| `ALT + A` | Trigger Aria |
| `ALT + Tab` | Snappy Switcher (MRU) |
| `SUPER + Tab` | Snappy Switcher (Workspace filtered) |

### 🖼️ Window Management
| Keybind | Action |
| :--- | :--- |
| `SUPER + Q` | Close Window |
| `SUPER + ALT + Q` | Kill Window |
| `SUPER + F` | Toggle Fullscreen |
| `SUPER + ALT + F` | Toggle Maximized |
| `SUPER + ALT + Space` | Toggle Float |
| `SUPER + SHIFT + C` | Toggle Group |
| `SUPER + ALT + C` | Column Resize (0.5) |

### 🌐 Workspaces & Navigation
| Keybind | Action |
| :--- | :--- |
| `SUPER + [1-9]` | Focus Workspace |
| `SUPER + ALT + [1-9]` | Move Window to Workspace |
| `SUPER + Wheel` | Cycle Workspaces |
| `SUPER + Arrows` | Focus Direction |
| `SUPER + SHIFT + Arrows` | Move Window Direction |

### 📦 Scratchpads
| Keybind | Action |
| :--- | :--- |
| `SUPER + D` | Discord |
| `SUPER + S` | Spotify |
| `SUPER + G` | Steam |
| `CTRL + SHIFT + Esc` | btop |
| `SUPER + SHIFT + Q` | qBittorrent |

### 🌙 Noctalia & UI
| Keybind | Action |
| :--- | :--- |
| `ALT + Space` | Launcher |
| `SUPER + I` | Settings |
| `CTRL + Space` | Control Center |
| `SUPER + SHIFT + X` | Lock Session |
| `SUPER + ALT + X` | Session Panel |
| `SUPER + V` | Clipboard |
| `SUPER + R` | Reload Config |

---
