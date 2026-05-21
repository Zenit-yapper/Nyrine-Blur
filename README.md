# 🌫️ Nyrine Blur

[![Modrinth](https://img.shields.io/badge/Modrinth-Nyrine_Blur-00AF5C?logo=modrinth)](https://modrinth.com/)
[![GitHub](https://img.shields.io/badge/GitHub-Nyrine_Blur-181717?logo=github)](https://github.com/)
[![Fabric](https://img.shields.io/badge/Loader-Fabric-blue?logo=fabric)](https://fabricmc.net/)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-5B5B5B?logo=minecraft)](https://minecraft.net/)

**A smooth, high-performance motion blur mod for Fabric 1.21.1**

![Nyrine Blur Banner](https://via.placeholder.com/800x200/1a1a2e/ffffff?text=Nyrine+Blur)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎮 **Smooth Motion Blur** | Cinematic blur effect while moving/camera rotation |
| ⚡ **Performance Optimized** | Minimal FPS impact with smart rendering |
| 🎛️ **Fully Configurable** | Adjust intensity, samples, and fade time |
| 🔘 **Toggle Keybind** | Default: `B` key to enable/disable |
| 🎨 **No Visual Glitches** | Works with shaders and other mods |
| 💾 **Settings Persistence** | Saves your preferences |

---

## 📥 Installation

### Requirements
- **Minecraft:** 1.21.1
- **Fabric Loader:** 0.16.0+
- **Fabric API:** 0.96.0+
- **Java:** 21+

### Steps
1. Install [Fabric Loader](https://fabricmc.net/use/)
2. Download `nyrineblur-1.0.0.jar` from [Releases](https://github.com/)
3. Place the `.jar` file in your `mods` folder
4. Launch Minecraft

---

## ⚙️ Configuration

### In-Game Settings
Press `B` (default) to toggle motion blur on/off

### Config File
Located at: `config/nyrineblur/config.json`

```json
{
  "enabled": true,
  "intensity": 0.8,
  "samples": 16,
  "fadeTime": 0.3,
  "keybind": "B"
}
