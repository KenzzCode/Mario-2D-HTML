# Super Cube Bros 🎮

A modern 3D platformer adventure game built with web technologies. Experience fast-paced gameplay with smooth animations and a beautiful UI, all running directly in your browser.

## ✨ Features

- **3D Platformer Gameplay** - Navigate through dynamic 3D environments with platforming challenges
- **Smooth Animations** - Fluid character and object movements powered by Anime.js
- **Responsive Design** - Fully responsive UI that works on all screen sizes
- **High Score System** - Track your best performance with a persistent score system
- **Intuitive Controls** - Easy-to-learn WASD + SPACE controls
- **Beautiful UI** - Modern, polished interface with glass-morphism effects

## 🎮 How to Play

### Controls
- **WASD** - Move character left, right, forward, backward
- **SPACE** - Jump to overcome obstacles
- **Mouse/Touch** - Navigate menus

### Objective
Navigate through challenging platformer levels, collect points, and reach the end of each stage. Avoid falling off platforms to stay alive!

## 🚀 Getting Started

### Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required!

### Running the Game

1. **Open the file directly:**
   - Simply open `index.html` in your web browser

2. **Using a local server (recommended for better performance):**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   ```
   Then navigate to `http://localhost:8000` in your browser

3. **Online:**
   - Host the file on any static hosting service (GitHub Pages, Netlify, Vercel, etc.)

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| **Three.js** | 3D/2D hybrid rendering engine |
| **Anime.js** | Smooth UI and object animations |
| **Tailwind CSS** | Responsive, modern UI styling |
| **HTML5/JavaScript** | Game logic and interaction handling |

### CDN Dependencies
- Three.js (v128): 3D graphics library
- Anime.js (v3.2.1): Animation library
- Tailwind CSS: Utility-first CSS framework

## 📁 Project Structure

```
Mario-2D/
├── index.html          # Main game file (HTML + CSS + JavaScript)
└── README.md           # This file
```

## 🎨 UI Components

- **Start Screen** - Player name input and game instructions
- **HUD (Heads-Up Display)** - Shows player name and score during gameplay
- **Game Over Screen** - Displays final score and restart options
- **Interactive Buttons** - Smooth hover effects and animations

## 🎯 Game Mechanics

- **Player Movement** - Smooth character movement with physics-based jumping
- **Platforming** - Navigate platforms of varying heights and difficulty
- **Scoring System** - Earn points by completing objectives
- **Level Progression** - Advance through increasingly challenging stages

## 📱 Browser Support

- ✅ Chrome/Chromium (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## ⚙️ Performance Tips

1. **Use a modern browser** - Ensures best WebGL performance
2. **Run on localhost** - Recommended for optimal loading speeds
3. **Close other tabs** - Reduces memory competition
4. **Disable browser extensions** - May improve frame rates

## 🔧 Development

The entire game is contained in a single `index.html` file for easy deployment and modification.

### To Customize:
1. Edit the `index.html` file
2. Modify CSS in the `<style>` tag
3. Update JavaScript game logic in the `<script>` tags
4. Refresh the browser to see changes

## 📝 Game Settings

### Key Configuration Variables
- **Canvas Size** - Automatically matches window size (100vw × 100vh)
- **Background Color** - Light blue (#60a5fa)
- **Player Name Max Length** - 12 characters
- **Touch Controls** - Enabled for mobile devices

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| Game won't load | Ensure all CDN links are accessible and you have internet connection |
| Low FPS | Check browser hardware acceleration is enabled, close other applications |
| Controls not working | Click on the game canvas first to ensure it has focus |
| Mobile touch issues | Try enabling "Desktop Mode" or check browser permissions |

## 📄 License

This project is open for educational and personal use. Feel free to modify and redistribute with attribution.

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to improve the game by:
1. Testing different platforms
2. Suggesting UI/UX improvements
3. Reporting gameplay issues
4. Contributing optimizations

---

**Enjoy playing Super Cube Bros!** 🎮✨

*Made with ❤️ using Three.js, Anime.js, and Tailwind CSS*
