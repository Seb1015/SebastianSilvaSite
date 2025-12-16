# Sebastian Silva - Portfolio Website

A modern, responsive portfolio website showcasing my skills as a Computer Science student and software developer. Built with clean HTML, CSS, and JavaScript, featuring a dark/light theme toggle, smooth animations, and mobile-first responsive design.

## 🚀 Live Demo

Visit the live website: [sebastiansilva.dev](https://sebastiansilva.dev)

## ✨ Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Mobile-first design that works on all devices
- **Dark/Light Theme**: Toggle between themes with persistent preference
- **Interactive Elements**: Hover effects, scroll animations, and smooth transitions
- **Performance Optimized**: Fast loading with optimized assets
- **Accessibility**: Keyboard navigation and screen reader friendly
- **SEO Ready**: Proper meta tags and semantic HTML structure

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Custom properties, Grid, Flexbox, and animations
- **JavaScript (ES6+)**: Modern JavaScript with interactive features
- **Font Awesome**: Icons for social links and UI elements
- **Google Fonts**: Inter font family for typography

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── package.json        # Project configuration
├── README.md          # Project documentation
└── assets/            # Images and other assets (optional)
```

## 🚀 Quick Start

### Option 1: Simple HTTP Server (Recommended)

1. **Clone or download** this repository
2. **Navigate** to the project directory
3. **Start a local server** using one of these methods:

```bash
# Using Python (if installed)
python3 -m http.server 8000

# Using Node.js (if installed)
npx http-server . -p 3000 -o

# Using PHP (if installed)
php -S localhost:8000
```

4. **Open** your browser and visit `http://localhost:8000`

### Option 2: Using npm (For development)

1. **Install dependencies**:
```bash
npm install
```

2. **Start development server**:
```bash
npm run dev
```

3. **Open** your browser and visit `http://localhost:3000`

## 📝 Customization

### Personal Information

Update the following in `index.html`:

- **Name and title** in the hero section
- **About me** content in the about section
- **Skills** in the skills section
- **Experience** details in the experience section
- **Projects** information in the projects section
- **Contact** information in the contact section
- **Social links** (LinkedIn, GitHub, email)

### Styling

Customize the appearance in `styles.css`:

- **Colors**: Update CSS custom properties in `:root`
- **Fonts**: Change the Google Fonts import
- **Layout**: Modify grid and flexbox properties
- **Animations**: Adjust keyframes and transitions

### Functionality

Enhance features in `script.js`:

- **Contact form**: Connect to a backend service
- **Analytics**: Add Google Analytics or other tracking
- **Additional animations**: Create custom scroll effects
- **Performance**: Optimize loading and interactions

## 🎨 Color Scheme

The website uses a modern color palette with CSS custom properties:

- **Primary**: Blue (#3b82f6)
- **Secondary**: Slate (#64748b)
- **Accent**: Amber (#f59e0b)
- **Background**: White/Light Gray (light theme)
- **Text**: Dark Slate (light theme)

Dark theme automatically inverts colors for better accessibility.

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🚀 Deployment Options

### GitHub Pages

1. Push code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify

1. Connect your GitHub repository to Netlify
2. Configure build settings (no build command needed)
3. Deploy automatically on every push

### Vercel

1. Import your GitHub repository to Vercel
2. Configure as a static site
3. Deploy with zero configuration

### AWS S3 + CloudFront

1. Upload files to an S3 bucket
2. Configure bucket for static website hosting
3. Set up CloudFront distribution for CDN

## 🔧 Development Scripts

```bash
# Start development server
npm run dev

# Start simple HTTP server
npm start

# Lint HTML and CSS
npm run lint

# Format code
npm run format

# Build (no build process needed)
npm run build
```

## 📊 Performance Features

- **Optimized Images**: Placeholder for profile image with lazy loading
- **Minimal Dependencies**: Only essential external resources
- **Efficient CSS**: Custom properties and modern selectors
- **Debounced Events**: Optimized scroll and resize handlers
- **Lazy Loading**: Intersection Observer for animations

## 🎯 SEO Optimization

- **Meta Tags**: Proper title, description, and viewport
- **Semantic HTML**: Proper heading hierarchy and landmarks
- **Alt Text**: Descriptive alt attributes for images
- **Structured Data**: Ready for JSON-LD implementation
- **Fast Loading**: Optimized for Core Web Vitals

## 🔒 Security Features

- **Content Security Policy**: Ready for CSP headers
- **XSS Protection**: Sanitized user inputs
- **HTTPS Ready**: Secure by default
- **No External Dependencies**: Minimal attack surface

## 📈 Analytics Integration

The website is ready for analytics integration:

```javascript
// Google Analytics 4
gtag('config', 'GA_MEASUREMENT_ID');

// Custom event tracking
trackEvent('button_click', { button: 'contact' });
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

**Sebastian Silva**
- Email: sebastian@example.com
- LinkedIn: [linkedin.com/in/sebastian-silva](https://linkedin.com/in/sebastian-silva)
- GitHub: [github.com/sebastian-silva](https://github.com/sebastian-silva)

## 🙏 Acknowledgments

- **Font Awesome** for the beautiful icons
- **Google Fonts** for the Inter font family
- **Modern CSS** techniques and best practices
- **Web accessibility** guidelines and standards

---

**Built with ❤️ by Sebastian Silva**

*Computer Science Student | Software Developer | Cloud & AI Enthusiast*

