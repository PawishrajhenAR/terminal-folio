# 🖥️ Terminal Portfolio - Pawishrajhen

An interactive, terminal-style portfolio website that showcases my projects, skills, and experience in a unique developer-friendly interface. Built with vanilla JavaScript, CSS, and HTML.

![Terminal Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow) ![CSS](https://img.shields.io/badge/CSS3-Advanced-orange)

## ✨ Features

### 🎮 Interactive Terminal Experience
- **Command-line interface** with realistic terminal behavior
- **Command history** with arrow key navigation
- **Typing effects** for dynamic content display
- **ASCII art headers** for each section
- **Theme switching** (Dark, Light, Hacker themes)

### 🎯 Portfolio Sections
- **About Me** - Personal introduction with typing animation
- **Skills** - Comprehensive technical skills table
- **Projects** - Interactive project cards with GitHub links
- **Research** - Published research paper details
- **Resume** - PDF viewer with download option
- **Contact** - Interactive contact form with email integration

### 🕹️ Built-in Games
- **Snake** - Classic snake game with border wrap-around
- **Tetris** - Full-featured Tetris with scoring
- **2048** - Popular sliding tile puzzle game
- **Whack-a-Mole** - Reflex-based clicking game

### 🎨 Visual Features
- **Responsive design** for all screen sizes
- **Smooth animations** and hover effects
- **Theme-aware styling** with CSS custom properties
- **Professional color schemes** for different themes
- **Social media integration** in terminal header

## 🚀 Live Demo

Visit the live portfolio: **[https://pawish-terminal.vercel.app/]**

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Styling**: CSS Grid, Flexbox, CSS Custom Properties
- **Animations**: CSS Keyframes, JavaScript animations
- **Games**: Canvas API, DOM manipulation
- **Deployment**: Static hosting

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # Complete styling and themes
├── main.js            # Core functionality and games
├── Resume.pdf         # Resume document
└── README.md          # This file
```

## 🎮 Available Commands

### Main Commands
- `help` - Show available commands
- `about` - Display personal information
- `skills` - Show technical skills table
- `projects` - Display project portfolio
- `research` - Show research paper details
- `resume` - Open resume viewer
- `contact` - Start interactive contact form
- `games` - Enter game mode

### Game Commands
- `snake` - Play Snake game
- `tetris` - Play Tetris
- `2048` - Play 2048 puzzle
- `whack` - Play Whack-a-Mole
- `stop` - Exit current game

### Utility Commands
- `clear` - Clear terminal output
- `run --all` - Auto-display all sections
- `theme [dark/light/hacker]` - Switch themes

### Fun Commands
- `sudo rm -rf /` - Easter egg command
- `hack nasa` - Another easter egg
- `install coffee` - Developer humor
- And many more hidden commands!

## 🎨 Themes

### Dark Theme (Default)
- Professional dark interface
- Orange accent colors
- High contrast for readability

### Light Theme
- Clean light interface
- Purple accent colors
- Professional appearance

### Hacker Theme
- Matrix-style green colors
- Cyberpunk aesthetic
- Terminal hacker vibes

## 🎯 Key Features Explained

### Interactive Terminal
The portfolio mimics a real terminal with:
- Command prompt with username
- Command history navigation
- Real-time command processing
- Error handling and feedback

### Project Showcase
Projects are displayed as interactive cards featuring:
- Project descriptions with tech stack highlights
- GitHub repository links
- Hover animations and effects
- Responsive grid layout

### Built-in Games
Each game includes:
- **Snake**: Classic gameplay with border wrapping
- **Tetris**: Full rotation, line clearing, scoring
- **2048**: Sliding tile mechanics with animations
- **Whack-a-Mole**: Reflex-based gameplay with timer

### Contact System
Interactive contact form with:
- Step-by-step input prompts
- Form validation
- Email integration
- Professional formatting

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone the repository:
```bash
git clone https://github.com/PawishrajhenAR/terminal-portfolio.git
```

2. Navigate to the project directory:
```bash
cd terminal-portfolio
```

3. Open `index.html` in your browser or serve locally:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

4. Visit `http://localhost:8000` in your browser

## 🎮 Game Controls

### Snake
- **Arrow Keys**: Control snake direction
- **Esc**: Exit game

### Tetris
- **Arrow Keys**: Move and rotate pieces
- **Space**: Hard drop
- **Esc**: Exit game

### 2048
- **Arrow Keys**: Move tiles
- **Esc**: Exit game

### Whack-a-Mole
- **Mouse/Touch**: Click moles
- **Esc**: Exit game

## 📱 Responsive Design

The portfolio is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
- Touch devices

## 🔧 Customization

### Adding New Commands
Edit `main.js` and add to the `handleCommand` function:

```javascript
if (command === 'your-command') {
  printToTerminal('Your response', true);
  return;
}
```

### Adding New Projects
Update the `projectCards` variable in `main.js`:

```javascript
const projectCards = `
  <div class="terminal-card-grid">
    <div class="terminal-card">
      <div class="content">
        <h3>Your Project</h3>
        <p>Project description</p>
        <a href="your-github-link" target="_blank" class="github-link">
          <!-- GitHub SVG -->
        </a>
      </div>
    </div>
  </div>
`;
```

### Adding New Themes
Add theme variables to the `themes` object in `main.js`:

```javascript
const themes = {
  yourTheme: {
    '--bg': '#your-bg-color',
    '--fg': '#your-fg-color',
    // ... other variables
  }
};
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Guidelines
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 About the Developer

**Pawishrajhen** is a passionate developer with expertise in:
- AI/ML Development
- Full-stack Web Development
- Computer Vision
- Natural Language Processing
- Blockchain Development

### Connect With Me
- **GitHub**: [@PawishrajhenAR](https://github.com/PawishrajhenAR)
- **LinkedIn**: [pawish6364](https://www.linkedin.com/in/pawish6364/)
- **Instagram**: [@ipawish](https://www.instagram.com/ipawish/)
- **Email**: pawishgpt@gmail.com

## 🌟 Acknowledgments

- ASCII art generators for section headers
- Open source game implementations
- Terminal UI inspiration from various sources
- Community feedback and suggestions

---

⭐ **Star this repository if you found it helpful!**

🔄 **Feel free to fork and customize for your own portfolio!** 
