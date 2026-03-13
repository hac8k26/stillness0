# stillness.ft - Portfolio Website

```
   _____ _______ _____ _      _      _   _ ______  _____ _____       ______ _______ 
  / ____|__   __|_   _| |    | |    | \ | |  ____|/ ____/ ____|     |  ____|__   __|
 | (___    | |    | | | |    | |    |  \| | |__  | (___| (___       | |__     | |   
  \___ \   | |    | | | |    | |    | . ` |  __|  \___ \\___ \      |  __|    | |   
  ____) |  | |   _| |_| |____| |____| |\  | |____ ____) |___) |  _  | |       | |   
 |_____/   |_|  |_____|______|______|_| \_|______|_____/_____/  (_) |_|       |_|   
```

A brutalist-style portfolio website showcasing systems architecture and UI engineering expertise.

[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge-id/deploy-status)](https://stillness0.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🌐 Live Demo

**[https://stillness0.vercel.app/](https://stillness0.vercel.app/)**

## ✨ Features

- **Brutalist Design** - Heavy borders, minimal colors, paper texture aesthetic
- **Interactive Tech Stack** - Clickable cards with detailed technology explanations
- **Background Music** - Auto-play audio with play/pause controls
- **Hand-Drawn Annotations** - SVG animated arrows and handwriting effects
- **Terms & Privacy Modal** - First-visit consent tracking with localStorage
- **SEO Optimized** - Complete meta tags, sitemap, robots.txt
- **Fully Responsive** - Mobile-first design with smooth breakpoints
- **Performance Focused** - Vanilla JS, minimal dependencies, fast loading

## 🛠️ Tech Stack

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Animations, Grid, Flexbox, Variables
- **JavaScript (ES6+)** - Vanilla JS, no frameworks
- **Tailwind CSS** - Utility-first styling via CDN
- **SVG** - Inline graphics and animations

### Typography
- **Space Grotesk** - Headings and display text
- **IBM Plex Mono** - Code and technical content
- **Caveat** - Handwriting annotations

### Tools & Libraries
- **Lucide Icons** - Beautiful icon library
- **Google Fonts** - Web font delivery
- **Transparent Textures** - Paper texture overlay

### SEO & Legal
- **sitemap.xml** - Search engine sitemap
- **robots.txt** - Crawler directives
- **Terms of Service** - Legal compliance
- **Privacy Policy** - Data protection

### Hosting
- **Vercel** - Continuous deployment from GitHub
- **Custom Domain** - stillness0.vercel.app
- **Auto HTTPS** - SSL certificate
- **Global CDN** - Edge network delivery

## 📁 Project Structure

```
stillness0/
├── index.html              # Main portfolio page
├── tech-info.html          # Tech stack overview
├── tech-html5.html         # HTML5 details
├── tech-css3.html          # CSS3 details
├── tech-javascript.html    # JavaScript details
├── tech-tailwind.html      # Tailwind CSS details
├── tech-svg.html           # SVG graphics details
├── tech-tools.html         # Tools & libraries details
├── terms.html              # Terms of Service
├── privacy.html            # Privacy Policy
├── sitemap.xml             # SEO sitemap
├── robots.txt              # Crawler directives
├── favicon.svg             # Site favicon (.ft logo)
├── joel-ellie.jpg          # Hero image
├── The-Last-Of-us-Theme-Song.mp3  # Background music
└── README.md               # This file
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime, etc.)
- Git for version control

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/hac8k26/stillness0.git
cd stillness0
```

2. **Open in browser**
```bash
# Simply open index.html in your browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

3. **Or use a local server**
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve

# PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## 🎨 Customization

### Colors
Edit CSS variables in any HTML file:
```css
:root {
    --paper: #f2f0e9;  /* Background */
    --ink: #1a1a1a;    /* Text & borders */
    --red: #e63946;    /* Accent 1 */
    --blue: #0077b6;   /* Accent 2 */
}
```

### Content
- **Personal Info**: Update name, location, links in `index.html`
- **Projects**: Modify LOG_01, LOG_02, LOG_03 cards
- **Skills**: Edit technical sections
- **Music**: Replace `The-Last-Of-us-Theme-Song.mp3`

### Typography
Change fonts in the `<head>` section:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont&display=swap" rel="stylesheet">
```

## 📱 Responsive Design

- **Mobile**: < 768px - Single column layout
- **Tablet**: 768px - 1024px - Two column grid
- **Desktop**: > 1024px - Three column grid

## 🔧 Development

### Adding New Pages
1. Create new HTML file
2. Add favicon link in `<head>`
3. Update `sitemap.xml` with new URL
4. Update `robots.txt` if needed
5. Add navigation links

### Testing
- Test on multiple browsers
- Check mobile responsiveness
- Validate HTML/CSS
- Test all interactive elements
- Verify SEO meta tags

## 📊 Performance

- **Lighthouse Score**: 95+ Performance
- **First Contentful Paint**: < 1.5s
- **Time to Interactive**: < 3s
- **Total Bundle Size**: < 500KB

## 🔒 Privacy & Legal

- Terms of Service: [terms.html](https://stillness0.vercel.app/terms.html)
- Privacy Policy: [privacy.html](https://stillness0.vercel.app/privacy.html)
- No tracking or analytics
- localStorage for consent only

## 🌟 Features Breakdown

### Music Player
- Auto-play on page load (after consent)
- Play/Pause toggle button
- Loop playback
- Brutalist styled controls

### Hand-Drawn Annotations
- "Click Here" arrow pointing to LOG_01
- "Contact Me" arrow to social icons
- "Accept" arrow in terms modal
- SVG path animations with stroke-dasharray

### Tech Stack Pages
- Interactive cards linking to detail pages
- Code examples and explanations
- Best practices documentation
- Resource links for learning

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Stillness.ft**
- GitHub: [@hac8k26](https://github.com/hac8k26)
- LinkedIn: [ram-0-6341373b6](https://www.linkedin.com/in/ram-0-6341373b6/)
- Email: itsram.ft@gmail.com
- Location: Visakhapatnam, Andhra Pradesh

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For support, email itsram.ft@gmail.com or open an issue on GitHub.

## 🙏 Acknowledgments

- Design inspiration: Brutalist web design movement
- Music: The Last of Us Theme Song
- Icons: Lucide Icons
- Fonts: Google Fonts
- Textures: Transparent Textures
- Hosting: Vercel

---

<div align="center">

**Made with ❤️ by stillness.ft**

[Website](https://stillness0.vercel.app/) • [GitHub](https://github.com/hac8k26) • [LinkedIn](https://www.linkedin.com/in/ram-0-6341373b6/)

</div>
