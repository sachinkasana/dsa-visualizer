# 🧠 DSA Visualizer - 3D Memory & Data Structures Learning Tool

[![GitHub Stars](https://img.shields.io/github/stars/sachinkasana/dsa-visualizer?style=flat-square)](https://github.com/sachinkasana/dsa-visualizer)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red.svg?style=flat-square)](https://github.com/sachinkasana)

An **interactive 3D visualization tool** for understanding memory management, data structures, and algorithms. Perfect for DSA learners, educators, and visual learners.

🎮 **Live Demo**: [https://dsa-visualizer-sk.vercel.app/](https://https://dsa-visualizer-sk.vercel.app/)

## ✨ Features

- **🎨 3D Memory Visualization** - Watch variables come to life in real-time 3D space
- **💾 Interactive Memory Management** - Add, delete, and manage variables with smooth animations
- **📊 Real-time Statistics** - Track memory usage and variable count
- **🎯 Smart Highlighting** - Click blocks to highlight them in 3D with camera focus
- **⌨️ Keyboard Support** - Press Enter to quickly add variables
- **📱 Fully Responsive** - Works seamlessly on desktop, tablet, and mobile
- **🌓 Dark Theme** - Easy on the eyes with beautiful color scheme
- **📈 Google Analytics Integration** - Track user engagement and learning patterns
- **⚡ Zero Dependencies** - Only Three.js for 3D rendering

## 🚀 Quick Start

### Live Demo (Recommended)
Visit [https://dsa-visualizer-sk.vercel.app/](https://https://dsa-visualizer-sk.vercel.app/) - No installation needed!

### Local Development
```bash
# Clone the repository
git clone https://github.com/sachinkasana/dsa-visualizer.git
cd dsa-visualizer

# Start a local server
python -m http.server 8000
# Or: npx http-server

# Open browser
open http://localhost:8000
```

### Deploy to Vercel
```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel
```

## 📖 How to Use

1. **Add Variables**: Enter a name and value, click "Add Variable"
2. **Interact**: Click any memory block to highlight it in 3D
3. **Delete**: Hover over a block and click "✕" to remove
4. **Controls**: Use "Rotate View" and "Reset Camera" for 3D navigation

## 🎯 Learning Path

Perfect for understanding:
- ✅ Variable declaration and memory allocation
- ✅ Memory addresses and pointers
- ✅ Stack memory management
- ✅ Variable scope and lifetime
- ✅ Basic data structure visualization

## 🏗️ Project Structure

```
dsa-visualizer/
├── index.html              # Main application (single file)
├── README.md               # This file
├── LICENSE                 # MIT License
├── package.json            # Project metadata
├── .gitignore              # Git ignore rules
├── vercel.json             # Vercel deployment config
└── docs/
    ├── CONTRIBUTING.md     # Contribution guidelines
    └── ANALYTICS.md        # Google Analytics setup
```

## 🔧 Technical Stack

- **Frontend**: Vanilla JavaScript (ES6+)
- **3D Graphics**: Three.js (WebGL)
- **Styling**: Modern CSS3 with CSS Variables
- **Analytics**: Google Analytics 4
- **Deployment**: Vercel (recommended)

## 📊 Google Analytics Setup

1. Get your GA ID from [Google Analytics](https://analytics.google.com)
2. Update in `index.html`: Replace `G-XXXXXXXXXX` with your ID
3. Deploy and check real-time dashboard

**Tracked Events:**
- `app_load` - Application initialized
- `variable_added` - Variable created
- `variable_selected` - Block clicked
- `variable_deleted` - Variable removed
- `clear_all_clicked` - All cleared
- `rotate_view_clicked` - Camera rotated
- `reset_camera_clicked` - Camera reset

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome/Edge | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Mobile | ✅ Full |

## 🤝 Contributing

Contributions welcome! See [CONTRIBUTING.md](docs/CONTRIBUTING.md)

## 📄 License

MIT License © 2026 Sachin Kasana - See [LICENSE](LICENSE)

## ❤️ Made in India

Built with passion in India for the global developer community.

## 🔗 Connect

- **GitHub**: [@sachinkasana](https://github.com/sachinkasana)
- **Twitter**: [@sachinkasana](https://twitter.com/sachinkasana)
- **Email**: contact@sachinkasana.dev

---

**Star ⭐ this repo if you find it helpful!**

Made with ❤️ by Sachin Kasana