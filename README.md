# 🚀 RocketRAM Landing Page

A modern, cyberpunk-themed landing page for the **RocketRAM** desktop application - a powerful system monitoring and PC optimization tool.

![RocketRAM Landing Page](https://img.shields.io/badge/RocketRAM-Landing%20Page-00f0ff?style=for-the-badge&logo=rocket)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Live Demo](#live-demo)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Deployment](#deployment)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Links](#links)
- [Contributing](#contributing)
- [License](#license)

## 🎯 About

This is the official landing page for **RocketRAM**, a feature-rich desktop application that provides real-time system monitoring, advanced process management, and comprehensive PC optimization tools. The landing page features a sleek cyberpunk-inspired design with modern animations and a fully responsive layout.

### 🔗 Related Links

- **🌐 Live Landing Page**: [rocketram.netlify.app](https://rocketram.netlify.app)
- **🚀 RocketRAM Application**: [github.com/melloom/RocketRAM](https://github.com/melloom/RocketRAM)
- **📦 Download Latest Release**: [Releases Page](https://github.com/melloom/RocketRAM/releases)

## ✨ Features

### 🎨 Design Features

- **Cyberpunk Theme**: Dark theme with neon cyan/pink accents
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Particle effects, scroll animations, and hover interactions
- **Modern UI/UX**: Glassmorphism effects, gradient backgrounds, and polished components
- **Interactive Elements**: Dynamic buttons, scroll indicators, and animated cards

### 📱 Page Sections

- **Hero Section**: Eye-catching introduction with call-to-action buttons and stats
- **Why RocketRAM**: Quick feature highlights in card format
- **Detailed Features**: Comprehensive feature list with categories
- **Screenshots**: Mockup-style previews of the application
- **Download Section**: Direct download links for Windows and macOS
- **System Requirements**: Minimum and recommended specifications
- **Footer**: Links and branding information

### 🎭 Interactive Features

- Particle canvas background with connected nodes
- Scroll-triggered animations using Intersection Observer
- Parallax scrolling effects
- Mobile-responsive navigation menu
- Button ripple effects
- Smooth scroll navigation
- Stats counter animations

## 🌐 Live Demo

Visit the live landing page at: **[https://rocketram.netlify.app](https://rocketram.netlify.app)**

The landing page is fully deployed and ready to use!

## 🖼️ Screenshots

The landing page features modern mockup-style previews of the RocketRAM application interface, including:

- Main Widget view with system metrics
- Process Management panel
- Settings and Configuration panel

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for local development)
- Git (optional, for cloning)

### Installation

#### Option 1: Direct Download

1. Download or clone this repository
2. Extract files to a folder
3. Open `index.html` in your web browser

#### Option 2: Clone Repository

```bash
git clone https://github.com/melloom/RocketRam-Website.git
cd RocketRam-Website
```

#### Option 3: Using a Local Server

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 📖 Usage

### Viewing the Landing Page

Simply open `index.html` in any modern web browser. No build process or dependencies required!

### Customizing Content

1. **Update Download Links**: Edit the download button links in `index.html` (around line 359 and 372)
2. **Change Colors**: Modify CSS variables in `css/styles.css` (lines 6-20)
3. **Add Screenshots**: Replace mockup placeholders with actual images in `assets/images/`
4. **Update Text**: Edit HTML content in `index.html`

### Adding Screenshots

1. Add your app screenshots to `assets/images/`
2. Update the screenshot placeholders in `index.html`:

```html
<!-- Replace this -->
<div class="screenshot-placeholder">
    <div class="mockup-frame">...</div>
</div>

<!-- With this -->
<img src="assets/images/main-widget.png" alt="Main Widget" class="screenshot-image">
```

## 🎨 Customization

### Color Scheme

Edit CSS variables in `css/styles.css`:

```css
:root {
    --primary-color: #00f0ff;    /* Cyan */
    --secondary-color: #ff0080;   /* Pink */
    --accent-color: #ffd700;      /* Gold */
    --bg-dark: #0a0e27;          /* Dark background */
    /* ... more variables ... */
}
```

### Fonts

The page uses Google Fonts:
- **Orbitron**: For headings and UI elements
- **JetBrains Mono**: For monospace text (if needed)

Fonts are loaded from Google Fonts CDN, so no local installation needed.

### Animations

- Particle effects: Edit `js/scripts.js` (particle canvas section)
- Scroll animations: Modify Intersection Observer settings in `js/scripts.js`
- Hover effects: Update CSS transition properties in `css/styles.css`

## 🌐 Deployment

### Deploy to Netlify

1. **Install Netlify CLI**:
   ```bash
   npm install -g netlify-cli
   ```

2. **Navigate to project folder**:
   ```bash
   cd landing-page
   ```

3. **Deploy**:
   ```bash
   netlify deploy --prod
   ```

   Or drag and drop the `landing-page` folder to [Netlify Drop](https://app.netlify.com/drop)

### Deploy to Vercel

1. **Install Vercel CLI**:
   ```bash
   npm install -g vercel
   ```

2. **Navigate to project folder**:
   ```bash
   cd landing-page
   ```

3. **Deploy**:
   ```bash
   vercel --prod
   ```

### Deploy to GitHub Pages

1. Push this repository to GitHub
2. Go to repository Settings → Pages
3. Select source branch (usually `main` or `master`)
4. Select `/ (root)` folder
5. Click Save

Your site will be available at: `https://yourusername.github.io/RocketRam-Website/`

### Deploy to Other Platforms

This is a static website, so it can be deployed to:
- **Cloudflare Pages**: Connect your GitHub repo
- **GitHub Pages**: Enable in repository settings
- **Surge.sh**: `surge ./landing-page`
- **AWS S3**: Upload files to S3 bucket with static hosting enabled
- **Any static hosting service**

## 📁 Project Structure

```
landing-page/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styles and theme (1400+ lines)
├── js/
│   └── scripts.js      # Interactive JavaScript features
├── assets/
│   └── images/         # Screenshot images (add your screenshots here)
└── README.md           # This file
```

## 🛠️ Technologies Used

### Core Technologies

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS variables, Grid, Flexbox
- **JavaScript (ES6+)**: Vanilla JavaScript (no frameworks)

### Key Features

- **CSS Variables**: For easy theming
- **CSS Grid & Flexbox**: Responsive layouts
- **Intersection Observer API**: Scroll animations
- **Canvas API**: Particle effects
- **Google Fonts**: Orbitron and JetBrains Mono
- **CSS Animations**: Smooth transitions and keyframes

### Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (responsive)

## 🔗 Links

### Repository Links

- **Landing Page Repository**: [github.com/melloom/RocketRam-Website](https://github.com/melloom/RocketRam-Website.git)
- **RocketRAM Application**: [github.com/melloom/RocketRAM](https://github.com/melloom/RocketRAM)

### Download Links

- **Windows Portable**: [Download .exe](https://github.com/melloom/RocketRAM/releases/download/v1.0.1/RocketRAM-1.0.1-win-x64-portable.exe)
- **Windows ZIP**: [Download ZIP](https://github.com/melloom/RocketRAM/releases/download/v1.0.1/RocketRAM-1.0.1-win-x64.zip)
- **macOS DMG**: [Download .dmg](https://github.com/melloom/RocketRAM/releases/download/v1.0.1/RocketRAM-1.0.1-mac-arm64.dmg)
- **All Releases**: [View All Releases](https://github.com/melloom/RocketRAM/releases)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Make your changes**
4. **Test thoroughly** (check responsiveness, browser compatibility)
5. **Commit your changes**: `git commit -m 'Add amazing feature'`
6. **Push to branch**: `git push origin feature/amazing-feature`
7. **Open a Pull Request**

### Contribution Guidelines

- Follow the existing code style
- Test on multiple browsers
- Ensure mobile responsiveness
- Keep animations smooth and performant
- Update documentation if needed

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

The landing page design and code are open source and free to use.

## 🙏 Acknowledgments

- **RocketRAM App Team**: For creating the amazing desktop application
- **Electron**: For the desktop framework used in RocketRAM
- **Google Fonts**: For Orbitron and JetBrains Mono fonts
- **All Contributors**: For making this project better

## 📞 Support

Need help or have questions?

- **Issues**: Open an issue on [GitHub](https://github.com/melloom/RocketRam-Website/issues)
- **RocketRAM App Support**: Visit the [main repository](https://github.com/melloom/RocketRAM/issues)
- **Documentation**: Check the main RocketRAM README for app documentation

## 🎯 Future Enhancements

Potential improvements for the landing page:

- [ ] Add actual app screenshots
- [ ] Add video demo/tutorial
- [ ] Add testimonials section
- [ ] Add blog/news section
- [ ] Add changelog section
- [ ] Add dark/light theme toggle
- [ ] Add analytics integration
- [ ] Add A/B testing capabilities
- [ ] Add multi-language support

---

**Made with ❤️ for RocketRAM**

⭐ **Star this repo if you find it useful!** ⭐

🔗 **[Download RocketRAM Now](https://github.com/melloom/RocketRAM/releases)** | **[View Source Code](https://github.com/melloom/RocketRAM)**
