# Arun Ghontale - Multi-Page Portfolio (Apple Style)

A complete, multi-page portfolio website in Apple's minimalist aesthetic showcasing ML Engineering, Software Development, and Data Science experience.

## 🎨 Features

- **Apple-inspired design** - Clean, minimalist aesthetic with premium feel
- **Multi-page architecture** - Proper site structure with individual pages
- **Complete content** - All resume information including projects, experience, publications, education
- **Individual case studies** - Detailed project pages with full technical context
- **Fully responsive** - Perfect on desktop, tablet, and mobile
- **Smooth animations** - Fade-in effects and transitions
- **Fast loading** - Optimized CSS and minimal JavaScript

## 📁 File Structure

```
portfolio/
├── index.html              # Homepage with hero, stats, featured projects
├── projects.html           # Grid of all projects
├── experience.html         # Complete work history timeline
├── publications.html       # Research papers
├── about.html             # Education and background
├── contact.html           # Contact information
├── styles.css             # Shared stylesheet (Apple aesthetic)
├── nav.js                 # Shared navigation JavaScript
├── projects/
│   ├── iot-threat.html    # IoT Threat Intelligence case study
│   ├── eeg-patterns.html  # EEG Pattern Recognition case study
│   └── [more projects]    # Additional project pages
└── README.md              # This file
```

## 🚀 Quick Start

### Local Testing

1. **Download all files** to a folder
2. **Open `index.html`** in your browser
3. **Navigate** using the top navigation menu

That's it! No build process or dependencies required.

### Live Deployment

The site is pure HTML/CSS/JS with no build step needed.

## 🌐 Deployment Options

### Option 1: GitHub Pages (Recommended)

1. Create repository: `yourusername.github.io`
2. Upload all files to the repository
3. Go to Settings → Pages
4. Source: Deploy from branch `main`
5. Site live at: `https://yourusername.github.io`

**Custom domain setup:**
- Add `CNAME` file with your domain
- Configure DNS A records to GitHub Pages IPs
- Enable HTTPS in GitHub Pages settings

### Option 2: Netlify

1. Sign up at netlify.com
2. Drag & drop the entire folder
3. Site goes live instantly
4. Free subdomain: `yoursite.netlify.app`
5. Connect custom domain in settings

### Option 3: Vercel

1. Sign up at vercel.com
2. Import from GitHub or upload files
3. Automatic HTTPS and global CDN
4. Free subdomain: `yoursite.vercel.app`

### Option 4: Traditional Web Hosting

Upload all files via FTP to any web hosting service (Bluehost, HostGator, etc.)

## 🎯 Customization Guide

### 1. Update Personal Information

**In all HTML files, update:**
- Name and title in navigation
- Email: `arungora@buffalo.edu`
- Phone: `+1 (716) 446-3727`
- LinkedIn: `linkedin.com/in/arun-ghontale`
- GitHub: `github.com/arun-ghontale`

### 2. Modify Colors

**In `styles.css` (lines 11-17):**

```css
:root {
    --color-accent: #0071e3;  /* Main blue - change this */
    --color-accent-hover: #0077ed;
}
```

Apple uses: `#0071e3` (blue)
Alternatives:
- Red: `#ff3b30`
- Green: `#34c759`
- Purple: `#af52de`
- Orange: `#ff9500`

### 3. Add New Projects

**Add to `projects.html`:**

```html
<a href="projects/new-project.html" class="project-card fade-in">
    <div class="project-card-image gradient-purple">
        🚀<br>Project Name
    </div>
    <div class="project-card-content">
        <h3 class="project-card-title">Project Title</h3>
        <p class="project-card-description">Description here</p>
        <div class="project-card-meta">
            <span>Key metric</span>
            <span>•</span>
            <span>Year</span>
        </div>
    </div>
</a>
```

**Create case study page:** Copy `projects/iot-threat.html` as template

### 4. Update Experience

Edit `experience.html` - the timeline structure makes it easy to add/remove jobs

### 5. Add Publications

Edit `publications.html` - simple card format for each paper

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ⚡ Performance

- No external dependencies except Font Awesome (optional)
- Minimal JavaScript (~2KB)
- Optimized CSS (~20KB)
- Fast page loads (<1 second)

## 🎨 Design System

### Typography
- Headings: San Francisco Pro Display (Apple's font)
- Body: San Francisco Pro Text
- Fallback: -apple-system, BlinkMacSystemFont, Helvetica Neue

### Color Palette
- Primary text: `#1d1d1f`
- Secondary text: `#6e6e73`
- Background: `#ffffff`
- Accent (blue): `#0071e3`

### Spacing Scale
- XS: 0.5rem (8px)
- SM: 1rem (16px)
- MD: 1.5rem (24px)
- LG: 2rem (32px)
- XL: 3rem (48px)

## 🔧 Technical Details

### CSS Architecture
- CSS Custom Properties for theming
- Mobile-first responsive design
- Smooth transitions and animations
- Grid and Flexbox layouts

### JavaScript Features
- Intersection Observer for scroll animations
- Smooth scrolling navigation
- Active page highlighting
- Zero external libraries

## 📝 Content Writing Tips

### Project Case Studies
1. Start with the problem/challenge
2. Explain your solution approach
3. Show technical details
4. Highlight results with metrics
5. Link to GitHub/demo if available

### Experience Bullets
- Lead with impact/achievement
- Quantify results (percentages, numbers)
- Use action verbs
- Include technologies used

## 🐛 Troubleshooting

### Links not working
- Check file paths are correct
- Ensure all files are in the right folders
- Projects folder must be in same directory as index.html

### Styles not loading
- Verify `styles.css` is in the root folder
- Check the `<link>` tag in each HTML file
- Clear browser cache

### Navigation not highlighting
- Check `nav.js` is loaded
- Verify file names match exactly
- Open browser console for errors

## 🎓 SEO Optimization

Add to `<head>` of each page:

```html
<meta name="description" content="Your description">
<meta name="keywords" content="ML Engineer, Data Science, Software Developer">
<meta property="og:title" content="Arun Ghontale - ML Engineer">
<meta property="og:description" content="Your description">
<meta property="og:image" content="preview-image.png">
<meta name="twitter:card" content="summary_large_image">
```

## 📊 Analytics (Optional)

Add Google Analytics to track visitors:

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

## 🔒 Best Practices

✅ **DO:**
- Keep content updated
- Test on multiple devices
- Use high-quality project screenshots
- Optimize any images you add
- Add meta descriptions for SEO
- Test all links regularly

❌ **DON'T:**
- Use copyrighted images
- Make the homepage too long
- Forget to update contact info
- Use too many animations
- Neglect mobile responsiveness

## 📞 Support

For questions about customization:
- Email: arungora@buffalo.edu
- LinkedIn: [arun-ghontale](https://linkedin.com/in/arun-ghontale)
- GitHub: [@arun-ghontale](https://github.com/arun-ghontale)

## 📄 License

This portfolio template is free to use and modify for your own portfolio.

## 🎉 Final Checklist

Before going live:

- [ ] Updated all personal information
- [ ] Verified all links work
- [ ] Tested on mobile devices
- [ ] Optimized any images
- [ ] Added meta descriptions
- [ ] Tested all navigation
- [ ] Spell-checked all content
- [ ] Verified contact information
- [ ] Added Google Analytics (optional)
- [ ] Set up custom domain (optional)

---

**Built with attention to detail and Apple's design philosophy.**

Good luck with your job search! 🚀
