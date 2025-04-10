# 🎮 FlashGames

<p align="center">
  <img src="https://img.shields.io/badge/Flash-Games-red?style=for-the-badge&logo=adobe" alt="Flash Games"/>
  <img src="https://img.shields.io/badge/Powered%20by-Ruffle-orange?style=for-the-badge&logo=firefox" alt="Powered by Ruffle"/>
  <img src="https://img.shields.io/badge/Nostalgia-Level%20100-blue?style=for-the-badge" alt="Nostalgia Level 100"/>
</p>

<p align="center">
  <i>A collection of nostalgic Flash games from the 2010s, preserved and made playable in modern browsers.</i>
</p>

## 📖 About This Project

This repository contains a collection of classic Flash games created by Antoine Boucher in 2010 for Parascholar at Sainte College. These games represent a piece of web history and personal nostalgia from a time when Flash games dominated online entertainment.

Thanks to the [Ruffle](https://ruffle.rs/) emulator, these games remain playable even after Adobe Flash's end-of-life in December 2020.

## 🚀 Getting Started

### Option 1: Play Online

The easiest way to play these games is to visit our hosted version at:
- [https://antoinebou12.github.io/FlashGames/](https://antoinebou12.github.io/FlashGames/)

### Option 2: Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/antoinebou12/FlashGames.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd FlashGames
   ```

3. **Open index.html in your browser**
   - Simply double-click on `index.html` or open it with your preferred browser
   - No server setup required! Everything runs client-side

## 🎯 Game Collection

| Game | Description | Controls |
|------|-------------|----------|
| **Tag** | A classic chase game where you need to avoid being tagged while trying to tag others. | Arrow Keys + Space |
| **Ricochet Kill** | A puzzle shooter where you must eliminate targets by ricocheting bullets off walls. | Mouse + Click |
| **Ballon** | A balloon-themed game that challenges your reflexes and timing. | Arrow Keys |

## 💻 Technical Details

### Browser Compatibility

These games are powered by Ruffle, which is compatible with:
- ✅ Chrome, Firefox, Edge (latest versions)
- ✅ Safari 14+
- ✅ Mobile browsers (basic support)

### How Ruffle Works

Ruffle is a Flash Player emulator written in Rust that translates Flash ActionScript to JavaScript on the fly. This project embeds Ruffle directly, so no plugins or extensions are required to play these games.

```html
<!-- Example of how Ruffle is integrated -->
<script src="https://unpkg.com/@ruffle-rs/ruffle"></script>
<script>
    // The Ruffle configuration is handled in index.html
</script>
```

## 🤝 Contributing

Contributions to this project are welcome! Here's how you can help:

1. **Add More Games**: If you have preserved Flash games that you'd like to add to this collection, please submit a pull request.

2. **Improve the Interface**: Enhancements to the game selection UI are always appreciated.

3. **Documentation**: Help improve this README or add game-specific instructions.

4. **Report Issues**: If you encounter any problems with the games or the Ruffle integration, please [open an issue](https://github.com/antoinebou12/FlashGames/issues).

## 🏆 Acknowledgements

- **Original Creator**: Antoine Boucher, who developed these games in 2010 for Parascholar at Sainte College
- **[Ruffle Team](https://ruffle.rs/)**: For creating an incredible Flash emulator that preserves a significant era of web history
- **Flash Game Developers**: To all the creators who made the Flash gaming era special

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <i>Dedicated to my 12-year-old self and everyone who spent countless hours enjoying Flash games in the 2000s and 2010s.</i>
</p>
