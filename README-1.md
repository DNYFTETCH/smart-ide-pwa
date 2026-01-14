# DevFlow IDE - Smart Development Environment

A powerful, modern Progressive Web App (PWA) IDE built for efficient web development. Created by **dnyftetch** (dnyftetch@gmail.com).

## 🚀 Features

### Core IDE Features
- **Monaco Editor Integration** - The same powerful editor that powers VS Code
- **Multi-File Editing** - Work with multiple files simultaneously with tab management
- **Syntax Highlighting** - Support for HTML, CSS, JavaScript, TypeScript, Python, JSON, Markdown, and more
- **Live Preview** - See your HTML/CSS/JS changes in real-time with split-screen preview
- **File Management** - Create, edit, and organize files with an intuitive file explorer

### Developer Tools
- **Integrated Terminal** - Execute commands directly in the IDE
- **Command Palette** - Quick access to all IDE commands (Ctrl/Cmd + P)
- **Smart Auto-Save** - Your work is automatically saved to local storage
- **Context Menu** - Right-click functionality for quick actions
- **Git Integration UI** - Built-in interface for version control operations

### Smart Features
- **Code Formatting** - Format your code with proper indentation
- **Bracket Pair Colorization** - Visual aids for matching brackets
- **Minimap** - Bird's eye view of your code
- **Smooth Scrolling** - Enhanced scrolling experience
- **Font Ligatures** - Better code readability with JetBrains Mono font

### PWA Capabilities
- **Installable** - Install as a native app on desktop and mobile
- **Offline Support** - Continue working even without internet connection
- **Auto-Updates** - Service worker ensures you always have the latest version
- **Fast Loading** - Cached resources for instant startup

## 🎨 Design

DevFlow IDE features a stunning dark theme with:
- Gradient-based accent colors (cyan to purple)
- Professional typography with Outfit and JetBrains Mono fonts
- Smooth animations and transitions
- Responsive layout that works on all screen sizes
- Glassmorphism effects with backdrop blur

## 📦 Installation

### Quick Start
1. Open `smart-ide.html` in a modern web browser (Chrome, Edge, Firefox, Safari)
2. Click the install button in your browser's address bar
3. Or access via browser and use "Add to Home Screen" / "Install App"

### Hosting
To host DevFlow IDE on your own server:

```bash
# Simply upload these files to your web server:
- smart-ide.html
- manifest.json
- sw.js
```

For local development:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Then open http://localhost:8000/smart-ide.html
```

## 🎯 Usage

### Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + P` | Open command palette |
| `Ctrl/Cmd + N` | Create new file |
| `Ctrl/Cmd + S` | Save current file |
| `Ctrl/Cmd + `` ` `` | Toggle terminal |
| `Ctrl/Cmd + Shift + P` | Toggle preview |
| `Esc` | Close modals/palettes |

### Terminal Commands

- `help` - Show available commands
- `ls` - List all files
- `pwd` - Show current directory
- `git status` - Check git status
- `clear` - Clear terminal output

### Creating New Files

1. Click the 📄 icon in the file explorer header
2. Or use keyboard shortcut `Ctrl/Cmd + N`
3. Enter filename and select file type
4. File appears in the explorer and opens automatically

### Live Preview

1. Click "Preview" in the status bar
2. Or use the preview button in the top bar
3. Split screen shows your code and live result
4. Changes update automatically as you type

### File Persistence

- All files are automatically saved to browser's local storage
- Files persist across sessions
- Auto-save triggers on every change (configurable)
- Manual save with `Ctrl/Cmd + S`

## 🛠 Technologies

- **Monaco Editor** - Microsoft's powerful code editor
- **Progressive Web App** - Modern web capabilities
- **Local Storage API** - Persistent data storage
- **Service Workers** - Offline functionality and caching
- **Web Manifest** - Installation and app-like experience
- **Modern JavaScript** - ES6+ features
- **CSS3** - Advanced styling with gradients, animations
- **Google Fonts** - JetBrains Mono & Outfit fonts

## 🌐 Browser Support

DevFlow IDE works best on:
- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+

## 📱 Mobile Support

DevFlow IDE is fully responsive and works on:
- iOS Safari
- Chrome for Android
- Samsung Internet
- Firefox Mobile

## 🔧 Configuration

Edit the `config` object in `smart-ide.html` to customize:

```javascript
const config = {
    theme: 'vs-dark',        // Editor theme
    fontSize: 14,            // Editor font size
    fontFamily: 'JetBrains Mono, monospace',
    tabSize: 2,              // Tab indentation
    autoSave: true           // Enable auto-save
};
```

## 📂 Project Structure

```
devflow-ide/
│
├── smart-ide.html      # Main application file
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
└── README.md          # Documentation
```

## 🚀 Future Enhancements

Planned features:
- [ ] GitHub integration for direct repository access
- [ ] Cloud sync across devices
- [ ] Collaborative editing
- [ ] More language support (Ruby, Go, Rust, etc.)
- [ ] Plugin system for extensions
- [ ] Code snippets library with custom snippets
- [ ] Theme customization
- [ ] Export projects as ZIP
- [ ] Import from GitHub/GitLab
- [ ] Real terminal emulation
- [ ] Debugger integration
- [ ] Code intelligence (autocomplete, IntelliSense)

## 🤝 Contributing

This is a personal project by dnyftetch. Feel free to fork and customize for your needs!

## 📄 License

Created by **dnyftetch** (GitHub: dnyftetch, Email: dnyftetch@gmail.com)

Free to use for personal and commercial projects.

## 💡 Tips & Tricks

1. **Organize Your Files**: Use meaningful names and keep related files together
2. **Use the Terminal**: Quick commands without leaving the IDE
3. **Command Palette**: Fastest way to access features
4. **Split Preview**: Edit and preview simultaneously
5. **Auto-Save**: No need to worry about losing work
6. **Context Menu**: Right-click in editor for quick actions
7. **Install as App**: Better performance and desktop integration

## 🐛 Known Issues

- Monaco Editor requires internet connection for first load
- Large files (>1MB) may impact performance
- Terminal is simulated (not a real shell)
- Preview only works for HTML/CSS/JS projects

## 📞 Support

For questions or issues:
- GitHub: @dnyftetch
- Email: dnyftetch@gmail.com

## 🎉 Acknowledgments

- Microsoft for Monaco Editor
- Google Fonts for typography
- The web development community

---

**Built with ❤️ by dnyftetch**

Last updated: January 2026
