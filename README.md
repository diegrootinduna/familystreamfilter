# Streaming Service Word Filter

<div align="center">

![Extension Icon](https://img.shields.io/badge/Chrome-Extension-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.3-blue?style=for-the-badge)
![Free Forever](https://img.shields.io/badge/Free-Forever-brightgreen?style=for-the-badge)

**🎬 Keep your streaming experience clean and family-friendly!**

*A Chrome extension that automatically filters inappropriate words from Netflix, Disney+, and Amazon Prime Video using closed captions.*

[🚀 Install from Chrome Web Store](#installation) • [📖 Documentation](#how-it-works) • [🐛 Report Issues](../../issues) • [💝 Support Development](#support-development)

</div>

## ✨ Features

- **🎯 Smart Content Filtering** - Automatically detects and filters inappropriate words in real-time
- **🔇 Instant Muting** - Mutes audio and applies visual overlay when filtered words appear
- **⚙️ Fully Customizable** - Add custom words, adjust colors, opacity, and duration
- **🛡️ Privacy-First** - All filtering happens locally, no data collection
- **🎨 Clean Interface** - Modern, intuitive popup with easy controls
- **🔄 Easy Toggle** - Enable/disable anytime without uninstalling

## 🎭 Supported Platforms

| Platform | Status | Regions |
|----------|--------|---------|
| Netflix | ✅ Supported | All regions |
| Disney+ | ✅ Supported | All regions |
| Amazon Prime Video | ✅ Supported | All regions |
| Hulu | 🔄 Coming Soon | - |
| HBO Max | 🔄 Coming Soon | - |

## 🚀 Installation

### From Chrome Web Store (Recommended)
1. Visit the [Chrome Web Store](https://chrome.google.com/webstore) (link coming soon)
2. Click "Add to Chrome"
3. Confirm installation
4. Start filtering!

### Manual Installation (Developer Mode)
1. Download or clone this repository
2. Open Chrome and go to `chrome://extensions/`
3. Enable "Developer mode" in the top right
4. Click "Load unpacked" and select the extension folder
5. The extension icon will appear in your toolbar

## 🔧 How It Works

1. **Install the extension** - Quick one-click installation
2. **Configure your word list** - Add words you want to filter
3. **Customize settings** - Adjust overlay color, opacity, and duration
4. **Start streaming** - The extension works automatically in the background
5. **Enjoy cleaner content** - Audio mutes and screen dims when filtered words appear

## 📋 Usage

### Adding Filtered Words
1. Click the extension icon in your Chrome toolbar
2. Type a word in the "Add a word to filter" field
3. Click "Add" or press Enter
4. The word will appear in your filtered words list

### Customizing Settings
- **Overlay Color**: Choose the color of the visual overlay
- **Opacity**: Adjust transparency (0-100%)
- **Duration**: Set how long the effect lasts (1-30 seconds)
- **Enable/Disable**: Toggle the extension on/off

### Removing Words
- Click the "Delete" button next to any word in your list
- Words are removed immediately

## 🛠️ Technical Details

### File Structure
```
streaming-word-filter/
├── manifest.json          # Extension configuration
├── popup.html            # Settings interface
├── popup.js              # Settings logic
├── content.js            # Main filtering functionality
├── background.js         # Background service worker
└── icons/
    ├── icon16.png
    ├── icon64.png
    └── icon128.png
```

### Technologies Used
- **Manifest V3** - Latest Chrome extension standard
- **Chrome Storage API** - Sync settings across devices
- **Content Scripts** - Inject filtering logic into streaming pages
- **Mutation Observer** - Monitor DOM changes for subtitle detection

### Permissions Required
- `storage` - Save your settings and word list
- `tabs` - Communicate between popup and content scripts

## 🔒 Privacy & Security

- **No Data Collection** - We don't collect, store, or transmit any personal data
- **Local Processing** - All filtering happens on your device
- **No External Servers** - No communication with external services
- **Minimal Permissions** - Only requests necessary permissions
- **Open Source** - Full transparency in code and functionality

## 🐛 Known Issues & Limitations

- **Subtitle Dependency** - Requires closed captions to be enabled
- **Language Support** - Currently optimized for English content
- **Platform Updates** - May break temporarily when streaming services update their interfaces

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **🐛 Report Bugs** - [Create an issue](../../issues) with detailed reproduction steps
2. **💡 Suggest Features** - Share your ideas for improvements
3. **🔧 Submit Pull Requests** - Help fix bugs or add features
4. **📖 Improve Documentation** - Help make our docs clearer
5. **🌐 Add Platform Support** - Help extend to more streaming services

### Development Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/streaming-word-filter.git

# Load the extension in Chrome
# 1. Open chrome://extensions/
# 2. Enable Developer mode
# 3. Click "Load unpacked"
# 4. Select the cloned folder
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💝 Support Development

This extension is **completely free** and will **always remain free**. If you find it useful and want to support continued development:

[![Patreon](https://img.shields.io/badge/Patreon-Support-FF424D?style=for-the-badge&logo=patreon&logoColor=white)](https://patreon.com/HermanMyburgh)
[![PayPal](https://img.shields.io/badge/PayPal-Donate-0070BA?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/webapps/billing/plans/subscribe?plan_id=P-04Y62281CE859115PNBA4KSI)

Your support helps fund:
- 🆕 New streaming platform support
- 🔧 Feature development and improvements
- 🐛 Bug fixes and maintenance
- 📚 Documentation and tutorials

## 📞 Contact & Support

- **🐛 Bug Reports**: [GitHub Issues](../../issues)
- **💡 Feature Requests**: [GitHub Discussions](../../discussions)
- **📧 Email**: [Your Email Here]
- **🐦 Twitter**: [@YourTwitter]

## 🎯 Roadmap

### Upcoming Features
- [ ] Support for more streaming platforms (Hulu, HBO Max, etc.)
- [ ] Multi-language support
- [ ] Import/export word lists
- [ ] Regex pattern support
- [ ] Whitelist functionality
- [ ] Usage statistics
- [ ] Parental controls with PIN protection

### Long-term Goals
- [ ] Mobile browser support
- [ ] AI-powered content analysis
- [ ] Community word lists
- [ ] Integration with parental control services

## 🏆 Acknowledgments

- Thanks to all users providing feedback and bug reports
- Chrome extension community for development resources
- Streaming platforms for accessibility features that make this possible

---

<div align="center">

**Made with ❤️ for families and content-conscious viewers**

*If this extension helps you, please consider leaving a ⭐ star on GitHub!*

</div>
