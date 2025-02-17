# T-Rex Runner Game

A modern implementation of the classic Chrome dinosaur game built with p5.js. Features responsive design, accessibility improvements, and touch support.

## 🎮 Features

- Classic T-Rex running and jumping gameplay
- Responsive design that works on all devices
- Score and high score tracking
- Touch and keyboard controls
- Accessible design with keyboard navigation
- Progressive difficulty increase

## 🚀 Getting Started

### Prerequisites

No installation needed! Just a modern web browser.

### Running Locally

1. Clone the repository:
```bash
git clone https://github.com/yourusername/t-rex.git
cd t-rex
```

2. Start a local server (any of these methods):
```bash
# Using Python 3
python -m http.server

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

3. Open your browser and navigate to:
- `http://localhost:8000` (for Python/PHP)
- `http://localhost:8080` (for http-server)

## 🎯 How to Play

- Press `SPACE` or `UP ARROW` key to make the T-Rex jump
- Avoid the cacti obstacles
- Press `R` to restart when game is over
- Your score increases the longer you survive
- The game gets progressively faster

## 📁 Project Structure

```
t-rex/
├── index.html          # Main HTML file
├── style.css           # Styles and responsive design
├── sketch.js           # Game logic using p5.js
├── p5.js              # p5.js library
├── p5.play.js         # p5.play library for sprite handling
├── p5.sound.min.js    # p5.sound library
├── assets/            # Game images
│   ├── trex1.png
│   ├── trex3.png
│   └── ...
└── README.md
```

## 🛠️ Built With

- [p5.js](https://p5js.org/) - JavaScript library for creative coding
- HTML5 Canvas
- CSS3 with modern features
- Vanilla JavaScript

## 🎨 Customization

The game can be customized by modifying:
- `style.css` - Visual appearance and layout
- `sketch.js` - Game mechanics and difficulty
- Asset images - Visual elements

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Original Chrome T-Rex game by Google
- p5.js community for the amazing library
- All contributors and users of this game