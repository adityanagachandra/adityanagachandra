# Personal Website - Content Management Guide

## 🎨 Your Swanky Minimalistic Site

Welcome to your new personal website! I've created a clean, modern design using Helvetica-inspired typography (Inter font) that retains your existing information and provides an easy-to-use structure for adding new content.

## 📁 Current Structure

```
├── index.html          # Main website file
├── styles.css          # All styling and design
└── WEBSITE_README.md   # This guide
```

## 🚀 Quick Start

1. Open `index.html` in your browser to see your site
2. Edit content directly in `index.html` - look for the placeholder sections
3. Your email (nagaca1@ucla.edu) is already included in the contact section

## ✏️ Adding Content

### Hero Section
```html
<!-- Located at the top of the page -->
<header class="hero">
    <h1 class="name">Aditya Nagachandra</h1>
    <p class="tagline">👋 Welcome to my digital space</p>
</header>
```
- Change the tagline to whatever describes you best
- The name is already set from your GitHub profile

### Adding to Existing Sections

Each section has a placeholder div that you can replace:

#### About Section
Replace this:
```html
<div class="content-placeholder">
    <p class="placeholder-text">Add your story here...</p>
</div>
```

With something like:
```html
<div class="about-content">
    <p>I'm a [your role] passionate about [your interests]...</p>
    <p>Currently studying/working at [institution/company]...</p>
</div>
```

#### Experience Section
Replace the placeholder with:
```html
<div class="experience-list">
    <div class="experience-item">
        <h3>Job Title</h3>
        <p class="company">Company Name</p>
        <p class="duration">Start Date - End Date</p>
        <p>Brief description of your role and achievements...</p>
    </div>
    <!-- Add more experience items as needed -->
</div>
```

#### Projects Section
Replace the placeholder with:
```html
<div class="projects-grid">
    <div class="project-item">
        <h3>Project Name</h3>
        <p>Brief description of the project...</p>
        <a href="https://github.com/username/repo" target="_blank">View on GitHub</a>
    </div>
    <!-- Add more projects as needed -->
</div>
```

#### Skills Section
Replace the placeholder with:
```html
<div class="skills-list">
    <div class="skill-category">
        <h4>Programming Languages</h4>
        <p>Python, JavaScript, Java, etc.</p>
    </div>
    <div class="skill-category">
        <h4>Technologies</h4>
        <p>React, Node.js, Docker, etc.</p>
    </div>
    <!-- Add more skill categories as needed -->
</div>
```

## 🎨 Styling Guidelines

The CSS is already set up with:
- **Colors**: Clean black/gray palette with blue accents
- **Typography**: Inter font (Helvetica-inspired) with perfect spacing
- **Layout**: Responsive design that works on all devices
- **Animations**: Subtle fade-in effects for modern feel

### Adding Custom Styles

If you want to add custom styling for your content, add it to the bottom of `styles.css`:

```css
/* Custom content styles */
.experience-item {
    margin-bottom: 2rem;
    padding: 1rem 0;
    border-bottom: 1px solid var(--color-border);
}

.experience-item h3 {
    font-size: 1.2rem;
    margin-bottom: 0.5rem;
}

.company {
    font-weight: 500;
    color: var(--color-accent);
}

.duration {
    font-size: 0.9rem;
    color: var(--color-secondary);
    margin-bottom: 0.5rem;
}
```

## 🔧 Advanced Customization

### Adding New Sections
To add a new section, copy this template and insert it before the footer:

```html
<section class="section your-section-name" id="your-section-id">
    <h2>Section Title</h2>
    <div class="your-content">
        <!-- Your content here -->
    </div>
</section>
```

### Changing Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --color-primary: #1a1a1a;      /* Main text color */
    --color-secondary: #6b6b6b;    /* Secondary text */
    --color-accent: #2563eb;       /* Links and accents */
    --color-background: #ffffff;   /* Page background */
    --color-surface: #f8fafc;      /* Placeholder backgrounds */
}
```

## 📱 Mobile Responsiveness

Your site automatically adapts to:
- ✅ Desktop computers
- ✅ Tablets
- ✅ Mobile phones
- ✅ Print (for PDF generation)

## 🚀 Deployment

### GitHub Pages (Recommended)
1. Push your files to a GitHub repository
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" → main branch
4. Your site will be live at `https://username.github.io/repository-name`

### Other Options
- **Netlify**: Drag and drop your files
- **Vercel**: Connect your GitHub repository
- **Surge.sh**: Run `surge` in your project directory

## 🎯 Quick Tips

1. **Keep it simple**: The design is intentionally minimal - don't overcomplicate
2. **Content first**: Focus on writing good content; the design will make it shine
3. **Test on mobile**: Always check how your additions look on smaller screens
4. **Use semantic HTML**: Keep the structure clean and accessible
5. **Optimize images**: If you add images, compress them for web use

## 🆘 Need Help?

- **Stuck on HTML?** Check [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)
- **CSS questions?** The styles use CSS custom properties (variables) for easy customization
- **Want inspiration?** Look at other minimalist portfolio sites for content ideas

---

**Pro tip**: Start by filling in one section at a time. The placeholder boxes will guide you to where content is needed!