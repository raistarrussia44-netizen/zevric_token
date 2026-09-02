# 🔥 Zevric - Token Generator

A fast, secure, and lightweight token generator tool built for speed and simplicity.

## ✨ Features

- ⚡ **Lightning Fast** - Instant token generation
- 🎯 **Multiple Modes** - Access Token & JWT support
- 🔐 **Secure** - No data storage or logging
- 📱 **Responsive** - Mobile-optimized design
- 🌙 **Dark Theme** - Easy on the eyes
- 💾 **Copy & Paste** - One-click clipboard actions
- 🔍 **Token Validation** - Real-time input validation

## 🚀 Quick Start

1. Clone the repository
```bash
git clone https://github.com/raistarrussia44-netizen/zevric_token.git
cd zevric_token
```

2. Open `index.html` in your browser or deploy to Render/Vercel

```bash
# Deploy to Render
# - Connect this repo to Render
# - Set build command: `echo "No build needed"`
# - Set start command: `python -m http.server 8080`
```

## 📖 How to Use

1. **Select Mode** - Choose between Access Token or JWT Token
2. **Enter Token** - Paste or enter your token in the input field
3. **Generate** - Click the Generate button
4. **Copy** - Click Copy Token to clipboard

## 🛠️ Tech Stack

- HTML5
- CSS3 (Custom Variables, Flexbox, Grid)
- Vanilla JavaScript (No dependencies)
- Font Awesome Icons
- Google Fonts (Inter)

## 📝 API Endpoints (For Integration)

You can integrate with your own API endpoints by modifying the `generate()` function:

```javascript
// Add your API call here
const response = await fetch('YOUR_API_ENDPOINT', {
  method: 'POST',
  body: JSON.stringify({ token: input, mode: currentMode })
});
```

## ⚠️ Disclaimer

This tool is provided **for educational and testing purposes only**. 
Users are responsible for complying with applicable terms of service.

## 📄 License

MIT License - Feel free to use and modify

## 🤝 Contributing

Pull requests welcome! Found a bug? Open an issue.

## 👨‍💻 Author

**Zevric** - Token Generator

---

**Live Demo:** [Coming Soon]

**GitHub:** https://github.com/raistarrussia44-netizen/zevric_token