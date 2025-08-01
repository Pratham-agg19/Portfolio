# Pratham Agarwal - Personal Portfolio Website

A modern, responsive single-page portfolio website with animated background, smooth scrolling, and interactive features.

## 🌟 Features

- **Dark Gradient Animated Background** - Changes color as you scroll
- **Responsive Design** - Works perfectly on all devices
- **Smooth Scrolling Navigation** - Seamless section transitions
- **Interactive Portfolio Tabs** - Projects and Certificates sections
- **Animated Tech Stack** - Hover effects and animations
- **Contact Form** - Functional with Formspree integration
- **Mobile-Friendly Navigation** - Hamburger menu for mobile devices
- **Scroll Animations** - Fade-in effects as you scroll
- **Modern UI/UX** - Clean, professional design

## 📁 File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
└── resume.pdf          # Your resume (add this file)
```

## 🚀 Quick Start

1. **Download/Clone** the project files
2. **Open** `index.html` in your web browser
3. **Customize** the content as needed (see customization guide below)

## 🎨 Customization Guide

### 1. Personal Information
Edit the following in `index.html`:

```html
<!-- Hero Section -->
<h1 class="hero-title">Your Name</h1>
<p class="hero-subtitle">Your Title | Your Skills</p>

<!-- About Section -->
<h3>Your Name</h3>
<p class="intro-line">Your Introduction Line</p>
```

### 2. Profile Photo
Replace the placeholder image URL in the About section:
```html
<img src="your-photo-url.jpg" alt="Your Name" class="profile-photo">
```

### 3. Portfolio Projects
Update the project cards in the Portfolio section:
```html
<div class="portfolio-card">
    <div class="card-image">
        <img src="project-image.jpg" alt="Project Name">
    </div>
    <div class="card-content">
        <h3>Project Title</h3>
        <p>Project description...</p>
        <div class="card-links">
            <a href="github-link" class="btn btn-small"><i class="fab fa-github"></i> GitHub</a>
            <a href="demo-link" class="btn btn-small btn-outline">Live Demo</a>
        </div>
    </div>
</div>
```

### 4. Certificates
Update the certificate cards:
```html
<div class="certificate-card">
    <i class="fas fa-certificate"></i>
    <h3>Certificate Name</h3>
    <p>Certificate description</p>
</div>
```

### 5. Work Experience
Update the experience section with your details:
```html
<div class="experience-item">
    <h3>Job Title</h3>
    <p class="company">Company Name</p>
    <p class="duration">Duration</p>
    <ul>
        <li>Responsibility 1</li>
        <li>Responsibility 2</li>
    </ul>
</div>
```

### 6. Contact Information
Update your social links:
```html
<a href="your-linkedin-url" target="_blank" class="social-link">
    <i class="fab fa-linkedin"></i>
    <span>LinkedIn</span>
</a>
<a href="your-github-url" target="_blank" class="social-link">
    <i class="fab fa-github"></i>
    <span>GitHub</span>
</a>
<a href="mailto:your-email@example.com" class="social-link">
    <i class="fas fa-envelope"></i>
    <span>Email</span>
</a>
```

### 7. Contact Form Setup
To make the contact form functional:

1. **Sign up** for [Formspree](https://formspree.io/)
2. **Create** a new form
3. **Replace** the form action URL in `index.html`:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### 8. Resume Download
Add your resume file:
1. **Save** your resume as `resume.pdf` in the project folder
2. **Update** the download link if needed:
```html
<a href="resume.pdf" class="btn btn-primary" download>Download Resume</a>
```

## 🎯 Tech Stack Icons

The website includes icons for:
- Python, SQL, Power BI, TensorFlow, Scikit-learn
- Pandas, MySQL, Excel, Git, HTML, CSS

To add/remove tech stack items, edit the tech-grid section in `index.html`.

## 📱 Responsive Design

The website is fully responsive and includes:
- **Mobile Navigation** - Hamburger menu
- **Flexible Grid Layouts** - Adapts to screen size
- **Optimized Typography** - Readable on all devices
- **Touch-Friendly** - Optimized for mobile interaction

## 🌈 Color Scheme

The website uses a modern dark theme with:
- **Primary Color**: #4a90e2 (Blue)
- **Background**: Dark gradient animation
- **Text**: White and light gray
- **Accents**: Blue highlights and hover effects

To customize colors, edit the CSS variables in `styles.css`.

## ⚡ Performance Features

- **Image Preloading** - Faster loading times
- **Smooth Animations** - Optimized CSS transitions
- **Lazy Loading** - Efficient resource management
- **Minimal Dependencies** - Only Font Awesome and Google Fonts

## 🔧 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!

## 📞 Support

If you need help customizing the portfolio, feel free to reach out!

---

**Note**: Remember to replace all placeholder content with your actual information before deploying your portfolio website. 