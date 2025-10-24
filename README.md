# Arun Ghontale - Portfolio Website

A modern, responsive portfolio website showcasing ML Engineering, Software Development, and Data Science experience.

## 🚀 Features

- **Modern Design**: Clean, professional layout with gradient accents
- **Dark Mode**: Toggle between light and dark themes with persistent preference
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll animations, hover effects, and transitions
- **Interactive Elements**: Floating cards, parallax effects, and dynamic content
- **SEO Optimized**: Semantic HTML and meta tags
- **Fast Loading**: Optimized CSS and JavaScript

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### 1. Personal Information

**In `index.html`:**

- **Line 6**: Update the page title
- **Lines 23-35**: Update navigation links (add/remove sections)
- **Lines 41-50**: Update hero section with your name and description
- **Lines 56-62**: Update contact links (GitHub, LinkedIn, email, etc.)
- **Lines 108-134**: Update education details
- **Lines 195-330**: Update work experience timeline
- **Lines 345-440**: Update project details
- **Lines 455-510**: Update publications
- **Lines 525-565**: Update contact information

### 2. Colors and Theme

**In `styles.css` (Lines 11-22):**

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #8b5cf6;    /* Secondary accent */
    --accent-color: #ec4899;       /* Accent highlights */
    /* Modify these to match your brand */
}
```

### 3. Skills

Update the skills section in `index.html` (Lines 158-193):

```html
<div class="skill-category">
    <div class="skill-icon">
        <i class="fas fa-your-icon"></i>
    </div>
    <h3>Your Category Name</h3>
    <div class="skill-tags">
        <span class="tag">Skill 1</span>
        <span class="tag">Skill 2</span>
        <!-- Add more skills -->
    </div>
</div>
```

### 4. Projects

To add a new project in `index.html`:

```html
<div class="project-card">
    <div class="project-header">
        <div class="project-icon">
            <i class="fas fa-project-diagram"></i>
        </div>
        <div class="project-links">
            <a href="YOUR_GITHUB_LINK" target="_blank">
                <i class="fab fa-github"></i>
            </a>
            <a href="YOUR_DEMO_LINK" target="_blank">
                <i class="fas fa-external-link-alt"></i>
            </a>
        </div>
    </div>
    <h3>Project Title</h3>
    <p class="project-description">
        Brief project description here.
    </p>
    <ul class="project-highlights">
        <li>Achievement or feature <strong>with metric</strong></li>
        <li>Another key point</li>
    </ul>
    <div class="project-tech">
        <span class="tech-badge">Tech 1</span>
        <span class="tech-badge">Tech 2</span>
    </div>
</div>
```

### 5. Adding Icons

This portfolio uses Font Awesome icons. Find icons at: https://fontawesome.com/icons

Common icons used:
- `fa-brain` - ML/AI
- `fa-code` - Software Development
- `fa-database` - Data Engineering
- `fa-shield-alt` - Security
- `fa-search` - Search/Analysis
- `fa-robot` - AI/Robotics

## 🌐 Deployment Options

### Option 1: GitHub Pages (Recommended)

1. Create a repository named `yourusername.github.io`
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select branch (main/master) as source
5. Your site will be live at `https://yourusername.github.io`

### Option 2: Netlify

1. Drag and drop the folder to Netlify
2. Site goes live instantly
3. Get a free subdomain or connect custom domain

### Option 3: Vercel

1. Connect your GitHub repository
2. Automatic deployment on every push
3. Free hosting with custom domain support

### Option 4: Custom Hosting

Upload files via FTP to any web hosting service.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🎯 Performance Tips

1. **Optimize Images**: Compress images before adding them
2. **Lazy Loading**: Images load as user scrolls
3. **Minify Files**: Use CSS/JS minifiers for production
4. **CDN**: Font Awesome is loaded from CDN for faster loading

## 🔧 Technical Details

### Technologies Used
- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+)
- Font Awesome 6.4.0

### Key Features Implementation
- **Dark Mode**: CSS custom properties + localStorage
- **Smooth Scroll**: Native CSS `scroll-behavior` + JS
- **Animations**: Intersection Observer API
- **Responsive**: CSS Grid and Flexbox with media queries

## 📝 Content Writing Tips

### Hero Section
- Keep it punchy and clear
- Lead with your strongest skill
- Include a call-to-action

### About Section
- Tell your story
- Show personality
- Highlight unique value

### Projects
- Start with the problem
- Show your solution
- Include metrics and impact
- Link to live demos

### Experience
- Lead with achievements
- Use action verbs
- Quantify results
- Keep it relevant

## 🎨 Design Philosophy

This portfolio follows modern web design principles:

1. **Minimalism**: Clean, focused design without clutter
2. **Hierarchy**: Clear visual hierarchy guiding the eye
3. **Consistency**: Consistent spacing, colors, and typography
4. **Accessibility**: Proper contrast ratios and semantic HTML
5. **Performance**: Fast loading and smooth interactions

## 🐛 Common Issues & Solutions

### Dark mode not persisting
- Check browser localStorage settings
- Ensure JavaScript is enabled

### Navigation not scrolling smoothly
- Check if `scroll-behavior: smooth` is supported
- JavaScript fallback is included

### Mobile menu not working
- Verify JavaScript is loaded
- Check console for errors

### Icons not showing
- Check Font Awesome CDN link
- Verify internet connection

## 📞 Support

For issues or questions:
- Email: arungora@buffalo.edu
- GitHub: [@arun-ghontale](https://github.com/arun-ghontale)
- LinkedIn: [Arun Ghontale](https://linkedin.com/in/arun-ghontale)

## 📄 License

This portfolio template is free to use and modify for your own portfolio.

## 🎉 Credits

Built by Arun Ghontale with:
- Font Awesome for icons
- Google Fonts for typography (if added)
- Love for clean code and design
