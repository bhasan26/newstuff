# Bilal Hasan - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases professional experience, projects, skills, and provides a contact form for potential employers or clients.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Animated skill bars
  - Typing effect on hero title
  - Scroll-triggered animations
  - Mobile-friendly hamburger menu
- **Contact Form**: Functional contact form with validation
- **Performance Optimized**: Fast loading with optimized animations

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # This file
└── Resume-Tech-Bilal.docx.pdf  # Your resume
```

## Customization Guide

### 1. Personal Information

Update the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Bilal Hasan</span></h1>
<p class="hero-subtitle">Software Engineer & Developer</p>
<p class="hero-description">
    Your personal description here...
</p>
```

#### About Section
```html
<p>Your about me text...</p>
```

#### Contact Information
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h3>Email</h3>
        <p>bhasan26@icloud.com</p>
    </div>
</div>
```

### 2. Experience Section

Replace the timeline items with your actual work experience:

```html
<div class="timeline-item">
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <p class="company">Company Name</p>
        <p class="duration">2022 - Present</p>
        <ul>
            <li>Your responsibility 1</li>
            <li>Your responsibility 2</li>
            <li>Your responsibility 3</li>
        </ul>
    </div>
</div>
```

### 3. Projects Section

Update the project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-code"></i>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-live-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

### 4. Skills Section

Update your skills and proficiency levels:

```html
<div class="skill-item">
    <span>Skill Name</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### 5. Statistics

Update the about section statistics:

```html
<div class="stat">
    <h3>2+</h3>
    <p>Years Experience</p>
</div>
```

## Color Scheme

The current color scheme uses:
- Primary Blue: `#2563eb`
- Secondary Blue: `#3b82f6`
- Accent Yellow: `#fbbf24`
- Dark Gray: `#1f2937`
- Light Gray: `#f8fafc`

To change colors, update the CSS variables in `styles.css`.

## Adding Your Photo

1. Add your profile photo to the project folder
2. Replace the placeholder in the hero section:

```html
<div class="hero-image">
    <img src="your-photo.jpg" alt="Bilal Hasan" class="profile-image">
</div>
```

3. Add CSS for the image:

```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}
```

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed instantly
3. You'll get a custom URL

### Vercel
1. Connect your GitHub repository to Vercel
2. Vercel will automatically deploy your site
3. You'll get a custom URL

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. Optimize images before adding them
2. Use WebP format for better compression
3. Minimize external dependencies
4. Enable gzip compression on your server

## Contact Form Setup

The contact form currently shows a success message. To make it functional:

1. Use a service like Formspree, Netlify Forms, or EmailJS
2. Update the form action and method in `index.html`
3. Modify the JavaScript form handling in `script.js`

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio, feel free to:
- Check the code comments for guidance
- Modify the CSS variables for easy customization
- Update the JavaScript for additional functionality

---

**Note**: Remember to replace all placeholder content with your actual information, projects, and experience. The portfolio is designed to be easily customizable while maintaining a professional appearance. 