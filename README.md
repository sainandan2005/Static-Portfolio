# 🚀 Sainandan Mannepalli - Portfolio Website

A stunning, modern, and fully responsive portfolio website showcasing AI/ML expertise, projects, and professional experience.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

### 🎨 Design & UI
- **Modern Gradient Design** with glassmorphism effects
- **Smooth Animations** using AOS (Animate On Scroll) library
- **Custom Cursor** with interactive hover effects
- **Responsive Layout** optimized for all devices (mobile, tablet, desktop)
- **Dark Theme** with vibrant accent colors
- **Floating Elements** with parallax effects

### 🛠️ Functionality
- **Dynamic Typing Animation** showcasing multiple roles
- **Sticky Navigation** with active link highlighting
- **Mobile-Friendly Menu** with hamburger navigation
- **Smooth Scroll** to sections
- **Animated Counters** for statistics
- **Skill Progress Bars** with animation on scroll
- **Interactive Project Cards** with 3D tilt effect
- **Contact Form** with mailto integration
- **Back-to-Top Button** for easy navigation
- **Timeline View** for experience section

### ⚡ Performance
- **Optimized Loading** with lazy loading
- **Minimal Dependencies** (only AOS and Font Awesome)
- **Fast Rendering** with efficient CSS
- **SEO Optimized** with proper meta tags
- **Accessibility Features** for screen readers

## 📁 Project Structure

```
Static Portfolio/
├── index.html          # Main HTML file with semantic structure
├── styles.css          # Complete styling with animations
├── script.js           # JavaScript for interactivity
├── Updated_Resume.txt  # Source resume data
└── README.md          # Documentation (this file)
```

## 🚀 Quick Start

### Option 1: Open Locally
1. Download or clone this repository
2. Open `index.html` in your web browser
3. That's it! No build process required.

### Option 2: Use Live Server (Recommended for Development)
1. Install [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. Your portfolio will open at `http://localhost:5500`

## 🌐 Deployment Options

### 1. **GitHub Pages** (Free & Easy)
```bash
# Create a new repository on GitHub
git init
git add .
git commit -m "Initial commit: Portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main

# Enable GitHub Pages
# Go to Settings > Pages > Select 'main' branch > Save
# Your site will be live at: https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

### 2. **Netlify** (Drag & Drop)
1. Go to [Netlify](https://www.netlify.com/)
2. Sign up/Login
3. Drag the entire project folder to the deploy area
4. Your site is live! (Custom domain available)

### 3. **Vercel** (Instant Deployment)
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
cd "Static Portfolio"
vercel

# Follow the prompts
# Your site will be live at: https://your-portfolio.vercel.app
```

### 4. **Cloudflare Pages** (Fast & Secure)
1. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
2. Connect your GitHub repository
3. Deploy automatically on every push

### 5. **Azure Static Web Apps** (Microsoft Azure)
```bash
# Install Azure Static Web Apps CLI
npm install -g @azure/static-web-apps-cli

# Deploy
swa deploy
```

## 🎨 Customization Guide

### Update Personal Information

#### 1. **Contact Details** (index.html)
```html
<!-- Update email -->
<a href="mailto:YOUR-EMAIL@gmail.com">YOUR-EMAIL@gmail.com</a>

<!-- Update phone -->
<a href="tel:+91XXXXXXXXXX">+91 XXXXXXXXXX</a>

<!-- Update LinkedIn -->
<a href="https://www.linkedin.com/in/YOUR-PROFILE/">LinkedIn</a>

<!-- Update GitHub -->
<a href="https://github.com/YOUR-USERNAME">GitHub</a>
```

#### 2. **Hero Section**
- Replace name in `<h1>` tags
- Update roles in `script.js` (typing animation array)
- Modify the description paragraph

#### 3. **About Section**
- Update education details
- Modify certifications
- Change statistics in stats section

#### 4. **Experience Section**
- Add/remove timeline items
- Update company names, dates, and descriptions
- Modify tags/skills

#### 5. **Projects Section**
- Add new project cards by copying existing structure
- Update project links (GitHub, live demo)
- Modify project descriptions and technologies

#### 6. **Skills Section**
- Update skill categories
- Adjust skill levels (--skill-width in CSS)
- Add/remove skill cards

### Change Colors (styles.css)

```css
:root {
    /* Update primary color */
    --primary-color: #667eea;      /* Change to your brand color */
    --secondary-color: #764ba2;     /* Complementary color */
    --accent-color: #f093fb;        /* Highlight color */
    
    /* Update gradients */
    --gradient-primary: linear-gradient(135deg, #YOUR-COLOR1 0%, #YOUR-COLOR2 100%);
}
```

### Add Your Photo

Replace the placeholder in the hero section:

```html
<!-- Replace this -->
<div class="profile-placeholder">
    <div class="placeholder-content">
        <i class="fas fa-user-astronaut"></i>
    </div>
</div>

<!-- With this -->
<img src="your-photo.jpg" alt="Sainandan Mannepalli" class="profile-image">
```

Add this CSS:
```css
.profile-image {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    object-fit: cover;
    animation: float 6s ease-in-out infinite;
    box-shadow: 0 20px 60px rgba(102, 126, 234, 0.4);
}
```

### Add Project Images

Replace placeholders with actual images:

```html
<!-- Replace -->
<div class="project-placeholder">
    <i class="fas fa-book-open"></i>
</div>

<!-- With -->
<img src="project-image.jpg" alt="Project Name">
```

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)
- ⚠️ IE 11 (limited support)

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties
- **JavaScript (ES6+)** - Interactive functionality
- **AOS Library** - Scroll animations
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Inter, Space Grotesk)

## 📦 Dependencies

### CDN Links (Already Included)
```html
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Space+Grotesk:wght@300;400;500;600;700&display=swap">

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<!-- AOS Animation Library -->
<link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css">
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
```

## 🎯 SEO Optimization

The portfolio includes:
- Meta descriptions
- Open Graph tags for social media
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images (add when you include images)
- Fast loading time

### Add More SEO

```html
<!-- Add to <head> -->
<meta name="robots" content="index, follow">
<link rel="canonical" href="https://your-domain.com">
<meta property="og:image" content="https://your-domain.com/preview.jpg">
```

## 📊 Analytics Integration

### Google Analytics
```html
<!-- Add before </head> -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## ♿ Accessibility Features

- Semantic HTML elements
- ARIA labels for interactive elements
- Keyboard navigation support
- Focus indicators
- Screen reader friendly
- Color contrast compliance (WCAG AA)

## 📝 Future Enhancements

- [ ] Add blog section
- [ ] Integrate CMS for easy content updates
- [ ] Add testimonials section
- [ ] Create downloadable resume
- [ ] Add dark/light mode toggle
- [ ] Integrate contact form with backend service
- [ ] Add project filters
- [ ] Implement PWA features
- [ ] Add loading animations
- [ ] Create multi-language support

## 🐛 Known Issues

- Custom cursor may not work on touch devices (intentional)
- Form uses mailto (requires email client)
- Some animations may be reduced on low-performance devices

## 📄 License

This project is free to use for personal purposes. Feel free to customize it for your own portfolio!

## 🤝 Contributing

If you find any bugs or have suggestions:
1. Open an issue
2. Fork the repository
3. Create a pull request

## 📧 Contact

**Sainandan Mannepalli**
- Email: sainandan205@gmail.com
- LinkedIn: [linkedin.com/in/sainandan2005](https://www.linkedin.com/in/sainandan2005/)
- Location: Hyderabad, India

---

## 🌟 Showcase

This portfolio demonstrates:
- Modern web design principles
- Responsive development
- Performance optimization
- Clean code practices
- Accessibility standards
- SEO best practices

Built with ❤️ using HTML, CSS, and JavaScript

---

### 🎉 Thank You!

If you found this portfolio helpful, consider giving it a ⭐ on GitHub!

**Last Updated:** October 2025
