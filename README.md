# GiftGenius 🎁

AI-Powered Personalized Gift Recommendations

[![Deploy to Cloudflare](https://img.shields.io/badge/Deploy-Cloudflare-orange)](https://pages.cloudflare.com/)
[![Powered by Coze](https://img.shields.io/badge/Powered%20by-Coze-blue)](https://www.coze.com/)

## 🌟 Features

- **AI-Powered**: Uses advanced AI to generate personalized gift recommendations
- **Interactive Quiz**: Simple 3-step questionnaire to understand the recipient
- **Global Shopping**: Direct links to Amazon and TikTok Shop
- **Mobile-Friendly**: Responsive design works on all devices
- **Multi-language**: Currently available in English

## 🚀 Quick Start

1. **Visit the website** and answer 3 simple questions:
   - Who are you shopping for?
   - What are their interests?
   - What's your budget?

2. **Get AI recommendations** with unique, thoughtful gift ideas

3. **Shop directly** via Amazon or TikTok links

## 💰 Monetization

This project includes affiliate marketing integration:
- Amazon Associates links
- TikTok Shop links (coming soon)

## 🛠️ Tech Stack

- **Frontend**: Vanilla HTML, CSS, JavaScript
- **AI**: Coze AI API
- **Hosting**: Cloudflare Pages
- **Version Control**: GitHub

## 📁 Project Structure

```
gift-genius-ai/
├── index.html          # Main application
├── README.md           # This file
├── LICENSE             # MIT License
└── .gitignore          # Git ignore rules
```

## 🌍 Deployment

### Cloudflare Pages
1. Sign up at [Cloudflare](https://dash.cloudflare.com)
2. Go to Pages → Upload assets
3. Drag and drop the project folder
4. Get your free `*.pages.dev` domain

### Other Platforms
This is a static site and can be deployed to:
- Vercel
- Netlify
- GitHub Pages
- Any static hosting

## 🔧 Configuration

### AI API Setup
Edit `index.html` and update the Coze API configuration:

```javascript
const COZE_CONFIG = {
    apiKey: 'YOUR_API_KEY',
    botId: 'YOUR_BOT_ID'
};
```

### Affiliate Links
Replace the placeholder affiliate tags:
- Amazon: Replace `giftgenius-20` with your Associates tag
- TikTok: Add your TikTok Shop affiliate links

## 📝 License

MIT License - feel free to use for personal or commercial projects!

## 🙏 Credits

- Built with [Coze AI](https://www.coze.com/)
- Deployed on [Cloudflare Pages](https://pages.cloudflare.com/)

---

Made with ❤️ by GiftGenius
