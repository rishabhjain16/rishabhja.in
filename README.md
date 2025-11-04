# Rishabh Jain - Modern Portfolio Website

A modern, techy, and interactive portfolio website showcasing AI/ML research, publications, and professional experience.

## 🚀 Features

### Design & Aesthetics
- **Dark Theme** with cyberpunk-inspired color scheme
- **Particle.js Background** for dynamic visual effects
- **Glassmorphism Effects** on cards and components
- **Gradient Accents** throughout the design
- **Smooth Animations** and transitions
- **Fully Responsive** - works on all devices

### Interactive Elements
- **Terminal-Style Hero Section** with typing animation
- **Animated Skill Bars** that progress on scroll
- **Interactive Timeline** for work experience
- **Tabbed Publications Section** (Journals, Conferences, Thesis)
- **Smooth Scroll Navigation** with active link highlighting
- **Hover Effects** on all interactive elements
- **Mobile-Friendly** hamburger menu

### Sections
1. **Hero** - Terminal-style introduction with typing animation
2. **About** - Professional background with statistics counter
3. **Skills** - Technical arsenal with progress bars and tech stack
4. **Experience** - Professional journey with timeline
5. **Publications** - Research papers and thesis (tabbed interface)
6. **Contact** - Get in touch with code snippet showcase

### Technical Features
- **Particles.js** for background animation
- **Intersection Observer API** for scroll-triggered animations
- **CSS Grid & Flexbox** for responsive layouts
- **Custom CSS Variables** for easy theming
- **Semantic HTML5** markup
- **Accessible** keyboard navigation
- **Performance Optimized** with lazy loading
- **Cross-Browser Compatible**

## 🎨 Color Palette

```css
Primary Background: #0a0a0f
Secondary Background: #13131a
Accent Primary (Cyan): #00d9ff
Accent Secondary (Purple): #7b2ff7
Accent Tertiary (Pink): #ff006e
```

## 📁 File Structure

```
rj/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── images/             # Image assets (create this folder)
│   └── about.png       # Profile image (optional)
└── README.md           # This file
```

## 🛠️ Setup & Usage

### Option 1: Direct Open
Simply open `index.html` in any modern web browser.

### Option 2: Local Server (Recommended)
For best results, run a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 📸 Adding Your Profile Image

1. Create an `images` folder in the project directory
2. Add your profile photo as `about.png`
3. The website will automatically display it in the About section
4. If no image is found, a placeholder avatar icon will be shown

## 🎯 Customization

### Update Personal Information

**Edit `index.html`:**
- Change name, role, and description in the Hero section
- Update About section with your bio
- Modify Experience timeline entries
- Add/remove Publications
- Update Contact links and social media

### Modify Colors

**Edit `styles.css` at `:root` section:**
```css
:root {
    --accent-primary: #00d9ff;    /* Change primary color */
    --accent-secondary: #7b2ff7;  /* Change secondary color */
    --accent-tertiary: #ff006e;   /* Change tertiary color */
}
```

### Adjust Animations

**Edit `script.js`:**
- Modify `typingSpeed` for typing animation
- Change `roles` array for different role descriptions
- Adjust particle count in `particlesJS` configuration

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid, Flexbox, and Animations
- **JavaScript (ES6+)** - Interactive functionality
- **Particles.js** - Particle background effects
- **Font Awesome 6** - Icons
- **Google Fonts** - Inter & JetBrains Mono fonts

## 🌟 Features Breakdown

### Hero Section
- Terminal-style window design
- Auto-typing role animation cycling through titles
- CTA buttons with gradient effects
- Scroll indicator with animation

### Skills Section
- Categorized skills (AI/ML, Programming, Tools, Soft Skills)
- Animated progress bars
- Icon-based tech stack display
- Hover effects on skill cards

### Publications Section
- Three tabs: Journals, Conferences, Thesis
- Card-based layout
- External links to papers
- Special highlighting for featured work

### Contact Section
- Interactive contact cards
- Code snippet showcase (Python)
- Syntax-highlighted code
- Social media links

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px

## ⚡ Performance Tips

1. **Optimize Images**: Compress images before adding them
2. **Lazy Loading**: Images load only when needed
3. **Minimal Dependencies**: Only Particles.js as external library
4. **Efficient CSS**: Uses modern CSS features for better performance
5. **Reduced Animations**: Automatically reduces animations on low-end devices

## 🎨 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 📝 To-Do / Future Enhancements

- [ ] Add a Projects/Portfolio section
- [ ] Implement dark/light theme toggle
- [ ] Add blog integration
- [ ] Create downloadable CV/Resume button
- [ ] Add email contact form
- [ ] Implement Google Analytics
- [ ] Add loading animation
- [ ] Create custom cursor effect

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you create something cool, I'd love to see it!

## 📄 License

This project is open source and available for personal and commercial use.

## 📧 Contact

**Rishabh Jain**
- Email: j_rishabh@outlook.com
- GitHub: [@rishabhjain16](https://github.com/rishabhjain16)
- LinkedIn: [rishabhjain16](https://www.linkedin.com/in/rishabhjain16/)

---

**Made with ❤️ and lots of ☕ by Rishabh Jain**

*If you found this useful, consider giving it a ⭐ on GitHub!*
