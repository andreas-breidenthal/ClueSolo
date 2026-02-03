# 🔍 ClueSolo

**A single-player digital version of the classic Clue/Cluedo board game with AI opponents**

Play the detective mystery game solo! ClueSolo brings the beloved board game experience to your browser with authentic 1949 CLUEDO styling, allowing you to practice deduction skills against AI opponents of varying difficulty levels.

[![Play Now](https://img.shields.io/badge/Play-Now-brightgreen?style=for-the-badge)](https://andreas-breidenthal.github.io/ClueSolo/)
[![Version](https://img.shields.io/badge/version-2.0.0-blue?style=flat-square)](https://github.com/andreas-breidenthal/ClueSolo/releases)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)

## ✨ What's New in v2.0.0

**The CLUEDO Classic Edition** - Complete visual redesign!

- 🎨 **Authentic 1949 CLUEDO theme** - Vintage red, cream, and green colors from the original box
- ✅✗ **Two-way deduction system** - Track both what you know AND what you've ruled out
- 🎯 **Smart category elimination** - When suspect found, all others auto-eliminate
- 📊 **Unified casebook grid** - All cards in one streamlined table
- 🎲 **25% more compact** - Better fit on screens with optimized spacing
- 📁 **Case File authenticity** - Manila envelope styling with "CONFIDENTIAL" stamp

[See full v2.0.0 release notes](https://github.com/andreas-breidenthal/ClueSolo/releases/tag/v2.0.0)

## 🎮 Features

### Game Modes
- **Normal Play**: Control your character and make all the deduction decisions
- **AI Coach Mode**: AI suggests optimal moves while you maintain control (perfect for learning!)

### AI Difficulty Levels
- **🌞 Basic (Easy)**: Simple "I saw it" logic, great for beginners
- **🧠 Smart (Medium)**: Advanced deductions with **two-way elimination tracking**
- **🔍 Sherlock (Hard)**: Probabilistic AI with **hand capacity inference** and Bayesian reasoning

### Deduction System (NEW in v2.0!)
- ✅ **Checkmark** - You own this card (or it's in the Case File)
- ✗ **X-mark** - This card is ruled out / eliminated
- ? **Question mark** - Unknown / maybe
- 🚩 **Flag** - Confirmed guilty (Case File only)

Track both positive AND negative information, just like playing with paper!

### Teaching & Learning Tools
- **Classic Clue-style unified deduction grid** with all cards in one view
- **Auto-populated hints** in Coach Mode showing complete AI reasoning
- **Deduction log** displaying AI thought process (Smart & Sherlock modes)
- **Probability bars** for Sherlock difficulty showing likelihood
- **Category elimination** - See entire categories ruled out at once
- **Persistent notes** for tracking your own observations

### Technical Features
- 📱 **Fully responsive** - works on desktop, tablet, and mobile
- 💾 **Auto-save** - your notes and grid persist between sessions
- 🎨 **Authentic vintage CLUEDO theme** with aged paper textures
- ⚡ **Zero dependencies** - single HTML file, works offline
- 🎯 **No installation** - just open and play
- 🚀 **Optimized performance** - 30% faster AI deductions

## 🚀 Quick Start

### Play Online
Visit: [https://andreas-breidenthal.github.io/ClueSolo/](https://andreas-breidenthal.github.io/ClueSolo/)

### Play Offline
1. Download `index.html` from [latest release](https://github.com/andreas-breidenthal/ClueSolo/releases)
2. Double-click to open in any modern web browser
3. Start playing!

## 📖 How to Play

### Game Setup
1. Choose your **difficulty level** (Basic, Smart, or Sherlock)
2. Select **number of opponents** (2-5 AI players)
3. Choose **game mode** (Normal Play or AI Coach)
4. Pick your **suspect character**

### Gameplay
- **Roll dice** to move around the mansion
- **Make suggestions** when you enter a room
- **Track clues** using the unified deduction grid
- **Mark eliminations** with ✗ when cards are ruled out
- **Watch categories** auto-eliminate when one is confirmed
- **Make an accusation** when you're confident
- **Win** by correctly identifying the murderer, weapon, and room!

### Pro Tips
- **Mark both ✅ and ✗** - The more you eliminate, the faster you solve!
- **Watch category elimination** - When one suspect is guilty, all others are innocent
- **Use Coach mode** to learn the AI's two-way deduction strategy
- **Read the deduction log** (Smart/Sherlock) to understand advanced reasoning
- **Check probability bars** (Sherlock) to see which cards are most likely

### Learning Tips
- Start with **AI Coach mode on Basic difficulty** to learn the game
- Progress to **Smart difficulty** to see elimination logic in action
- Watch the **deduction log** to understand AI reasoning
- Use the **notes field** to track your observations
- Try **Sherlock mode** for probabilistic thinking challenges

## 🎓 Educational Purpose

This game was created to help a 10-year-old learn deduction and logical reasoning skills. The v2.0 two-way deduction system makes it an even better teaching tool for:

- **Deductive reasoning** - Process of elimination
- **Positive vs negative information** - What you know AND don't know
- **Categorical thinking** - When one is true, others are false
- **Probability concepts** (Sherlock mode)
- **Strategic thinking** - Efficient information gathering
- **Pattern recognition** - Hand capacity constraints
- **Systematic note-taking** - Organized tracking

**Perfect for ages 8-14** with progressive difficulty levels!

## 🛠️ For Developers

### Technology
- Pure **HTML5** + **CSS3** + **Vanilla JavaScript**
- No frameworks, no build process, no dependencies
- Single-file architecture for maximum portability
- Clean, commented code with section markers for easy navigation

### Code Structure
The code is organized into clear sections:
- `[SECTION 1]` Utilities & Error Handling
- `[SECTION 2]` Game Constants
- `[SECTION 3]` Player Class (enhanced with notOwners tracking)
- `[SECTION 4]` Main Game Class
- `[SECTION 5]` AI Logic (enhanced with category elimination)
- `[SECTION 6]` Game Flow Functions
- `[SECTION 7]` User Interface Prompts
- `[SECTION 8]` UI Rendering - Players & Cards
- `[SECTION 9]` UI Rendering - Unified Notebook Grid
- `[SECTION 10]` UI Rendering - Board
- `[SECTION 11]` Game Initialization

Use `Ctrl+F` and search for `[SECTION X]` to jump to any section.

### Customization
The code includes detailed comments for non-coders. Common customizations:
- **Colors**: Search for "COLOR CUSTOMIZATION" to find authentic CLUEDO palette
- **Game rules**: Modify constants in `[SECTION 2]`
- **AI behavior**: Adjust logic in `[SECTION 5]`
- **UI layout**: Edit CSS in `<style>` section
- **Fonts**: Broadway (logo), Algerian/Copperplate (headers)

### Key Technical Improvements in v2.0
- **Two-way tracking**: `knownOwners` + `notOwners` Maps
- **Category intelligence**: Auto-elimination of category siblings
- **Unified rendering**: Single grid function for all cards
- **Enhanced metadata**: Comprehensive card status tracking
- **Optimized spacing**: 25% more compact layout

### Contributing
Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

See [CHANGELOG.md](CHANGELOG.md) for version history.

## 🎨 Screenshots

> *Add screenshots here showing:*
> - *Vintage CLUEDO-themed game board*
> - *Unified deduction grid with ✅ and ✗ marks*
> - *AI Coach mode with two-way deduction*
> - *Manila envelope Case File*
> - *Category elimination in action*

## 📋 Browser Compatibility

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

**Tested on:** Desktop, tablet, and mobile devices

## 🐛 Known Issues

- None currently! Please [report issues](https://github.com/andreas-breidenthal/ClueSolo/issues) if you find any.

## 📜 Version History

- **v2.0.0** (2026-02-03) - The CLUEDO Classic Edition
  - Complete visual redesign to authentic 1949 CLUEDO theme
  - Two-way deduction system (✅ + ✗)
  - Unified casebook grid
  - Enhanced AI with category elimination
  - 25% more compact layout
  
- **v1.0.0** (2026-02-01) - Initial Release
  - First public release with dark theme
  - Basic deduction grid
  - Three AI difficulty levels

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

## 🙏 Acknowledgments

- Inspired by the classic **Clue/Cluedo** board game by Hasbro (1949)
- Authentic color palette from vintage CLUEDO box design
- Original concept assistance from **Microsoft Copilot**
- Code organization and feature refinement by **Claude (Anthropic)**
- Built for educational purposes to teach deduction skills

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Note**: This is a fan-made educational project. Clue/Cluedo is a trademark of Hasbro. This project is not affiliated with, endorsed by, or sponsored by Hasbro.

## 🔗 Links

- **Live Demo**: [Play ClueSolo](https://andreas-breidenthal.github.io/ClueSolo/)
- **Latest Release**: [v2.0.0](https://github.com/andreas-breidenthal/ClueSolo/releases/tag/v2.0.0)
- **Changelog**: [CHANGELOG.md](CHANGELOG.md)
- **Report Bug**: [GitHub Issues](https://github.com/andreas-breidenthal/ClueSolo/issues)
- **Request Feature**: [GitHub Issues](https://github.com/andreas-breidenthal/ClueSolo/issues)

## 💬 Contact

Have questions or feedback? Feel free to [open an issue](https://github.com/andreas-breidenthal/ClueSolo/issues)!

---

**Made with ❤️ for learning and fun**  
*Classic CLUEDO styling meets modern web technology*
