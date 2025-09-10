# GK
# Complete Guide: Editing & Deploying Your Portfolio Website

## Overview
Your professional portfolio website has been created with modern design, mobile responsiveness, and all the sections you requested. This guide will help you edit content, customize design, and deploy the website.

## File Structure
```
portfolio-website/
├── index.html          # Main HTML file with all content
├── style.css           # All styling and design
├── app.js             # JavaScript for interactions
└── README.md          # This guide
```

## 🎯 Quick Start: Making Your First Edit

### 1. Edit Your Name and Tagline
**File:** `index.html`
**Location:** Around line 45-47

```html
<h1 class="hero-title">Gokul Kolipaka</h1>
<p class="hero-tagline">Agile Program Manager | Pharma R&D Leader | AI Generalist | Transformation Coach</p>
```

**How to Edit:**
- Open `index.html` in any text editor (Notepad++, VSCode, or even Notepad)
- Find the lines above
- Change "Gokul Kolipaka" to your name
- Change the tagline to your preferred professional description
- Save the file

### 2. Update Contact Information
**File:** `index.html`
**Location:** Around line 800-820

```html
<div class="contact-info">
    <div class="contact-item">
        <i class="fas fa-envelope"></i>
        <div>
            <h4>Email</h4>
            <p>gokulkolipaka@gmail.com</p>
        </div>
    </div>
    <div class="contact-item">
        <i class="fas fa-phone"></i>
        <div>
            <h4>Phone</h4>
            <p>+91 9963479872</p>
        </div>
    </div>
</div>
```

**How to Edit:**
- Replace email address with your email
- Replace phone number with your phone
- Save the file

## 📝 Detailed Content Editing

### Hero Section Statistics
**Location:** `index.html`, around line 50-70

```html
<div class="hero-stats">
    <div class="stat-item">
        <h3 class="counter" data-target="19">0</h3>
        <p>Years Experience</p>
    </div>
    <div class="stat-item">
        <h3 class="counter" data-target="70">0</h3>
        <p>Professionals Trained</p>
    </div>
</div>
```

**Edit Instructions:**
- Change `data-target="19"` to your years of experience
- Change `data-target="70"` to number of people you've trained
- Modify the text descriptions as needed

### About Me Section
**Location:** `index.html`, around line 90-150

Find the section that starts with:
```html
<section id="about" class="about">
```

**Edit Instructions:**
- Update the paragraph text with your professional story
- Modify achievements and key metrics
- Change industries served and languages as applicable

### Skills Section
**Location:** `index.html`, around line 300-400

```html
<div class="skill-category">
    <h4><i class="fas fa-tasks"></i> Agile & Project Management</h4>
    <ul>
        <li>Scrum Master (DASSM, SASM)</li>
        <li>Project Management (PMP)</li>
        <li>Kanban & Lean</li>
    </ul>
</div>
```

**Edit Instructions:**
- Add or remove skill categories
- Update individual skills within each category
- Change icons by replacing `fas fa-tasks` with other Font Awesome icons

### Experience Section
**Location:** `index.html`, around line 500-650

```html
<div class="experience-item">
    <div class="experience-header">
        <h4>Deputy General Manager</h4>
        <span class="company">Graviti Pharmaceuticals</span>
    </div>
    <div class="experience-meta">
        <span class="duration">Apr 2024 - Present</span>
        <span class="location">India</span>
    </div>
    <ul class="experience-duties">
        <li>Leading strategic transformation agenda and enterprise PMO function</li>
    </ul>
</div>
```

**Edit Instructions:**
- Change job title, company, duration, and location
- Update the list of responsibilities
- Add or remove experience items by copying the entire `experience-item` div

### Projects Section
**Location:** `index.html`, around line 650-750

```html
<div class="project-card">
    <div class="project-header">
        <h4>AI-Powered Event Registration WebApp</h4>
        <span class="project-category">INNOVATION</span>
    </div>
    <p>Built GenAI/Low-code app for real-time event registration, showcased at PMI Gyan Lahari conference.</p>
    <div class="project-impact">
        <span>Impact: Streamlined registration for 500+ delegates</span>
    </div>
    <div class="project-meta">
        <span>Duration: 3 months</span>
        <div class="project-tech">
            <span>GenAI</span>
            <span>Low-code/No-code</span>
        </div>
    </div>
</div>
```

**Edit Instructions:**
- Update project title, category, and description
- Change impact metrics and duration
- Modify technology tags
- Add or remove projects by copying the entire `project-card` div

### Hobbies Section
**Location:** `index.html`, around line 760-800

```html
<div class="hobby-item">
    <i class="fas fa-cricket-ball"></i>
    <h4>Cricket</h4>
    <p>Passionate about playing and watching cricket matches</p>
</div>
```

**Edit Instructions:**
- Change hobby name and description
- Update icons (find Font Awesome icons online)
- Add or remove hobbies by copying the entire `hobby-item` div

## 🎨 Design Customization

### Changing Colors
**File:** `style.css`
**Location:** Top of the file (CSS variables)

```css
:root {
  --color-primary: #1e40af;        /* Main blue color */
  --color-secondary: #059669;      /* Green accent */
  --color-accent: #dc2626;         /* Red accent */
  --color-text: #1f2937;          /* Dark text */
  --color-bg: #f9fafb;            /* Light background */
}
```

**Edit Instructions:**
- Replace color codes with your preferred colors
- Use online color pickers to find hex codes
- Save and refresh to see changes

### Changing Fonts
**File:** `index.html`
**Location:** In the `<head>` section, around line 8

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

**Edit Instructions:**
- Visit [Google Fonts](https://fonts.google.com/)
- Choose a new font and copy the link
- Replace the existing Google Fonts link
- Update the font-family in `style.css` if needed

## 🚀 Deployment Options

### Option 1: GitHub Pages (Recommended - Free)

**Step 1: Create GitHub Account**
1. Go to [github.com](https://github.com) and sign up
2. Verify your email address

**Step 2: Create Repository**
1. Click "New repository" (green button)
2. Name it: `your-username.github.io` (replace with your actual username)
3. Make it public
4. Check "Add a README file"
5. Click "Create repository"

**Step 3: Upload Files**
1. Click "uploading an existing file"
2. Drag and drop your `index.html`, `style.css`, and `app.js` files
3. Write a commit message like "Initial portfolio upload"
4. Click "Commit changes"

**Step 4: Enable GitHub Pages**
1. Go to repository Settings
2. Scroll to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch
5. Click "Save"

**Step 5: Access Your Website**
- Your website will be available at: `https://your-username.github.io`
- It may take 5-10 minutes to go live

### Option 2: Netlify (Easy Drag & Drop)

**Step 1: Create Netlify Account**
1. Go to [netlify.com](https://netlify.com)
2. Sign up with email or GitHub

**Step 2: Deploy Website**
1. On Netlify dashboard, look for "Deploy manually"
2. Create a folder with your website files
3. Zip the folder (index.html, style.css, app.js)
4. Drag the zip file to Netlify's deploy area
5. Your website will get a random URL

**Step 3: Custom Domain (Optional)**
1. In site settings, go to "Domain settings"
2. Click "Add custom domain"
3. Follow instructions to connect your domain

### Option 3: Vercel (Developer-Friendly)

**Step 1: Create Vercel Account**
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub, GitLab, or email

**Step 2: Deploy**
1. Click "New Project"
2. Import your GitHub repository (if using GitHub)
3. Or drag and drop files directly
4. Click "Deploy"
5. Your site will be live with a vercel.app URL

## 📱 Testing Your Website

### Mobile Testing
1. Open website on your phone
2. Check that navigation menu works (hamburger button)
3. Ensure all sections display properly
4. Test contact form submission

### Desktop Testing
1. Test smooth scrolling navigation
2. Check hover effects on buttons and cards
3. Verify all animations work
4. Test contact form validation

### Performance Testing
1. Use Google PageSpeed Insights
2. Enter your website URL
3. Check both mobile and desktop scores
4. Follow suggestions for improvements

## 🔧 Advanced Customizations

### Adding a Blog Section
**Location:** `index.html`, after projects section

```html
<section id="blog" class="blog">
    <div class="container">
        <div class="section-header">
            <h2>Latest Articles</h2>
            <p>Insights and thoughts on project management and technology</p>
        </div>
        <div class="blog-grid">
            <article class="blog-card">
                <h4>Article Title</h4>
                <p>Article excerpt...</p>
                <span class="blog-date">September 2025</span>
            </article>
        </div>
    </div>
</section>
```

### Adding Testimonials
**Location:** `index.html`, before contact section

```html
<section id="testimonials" class="testimonials">
    <div class="container">
        <div class="section-header">
            <h2>What Colleagues Say</h2>
        </div>
        <div class="testimonial-item">
            <p>"Gokul is an exceptional project manager..."</p>
            <div class="testimonial-author">
                <strong>John Doe</strong>
                <span>Senior Director, AstraZeneca</span>
            </div>
        </div>
    </div>
</section>
```

### Adding Social Media Links
**Location:** `index.html`, in contact section

```html
<div class="social-links">
    <a href="https://linkedin.com/in/yourprofile" target="_blank">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://twitter.com/yourhandle" target="_blank">
        <i class="fab fa-twitter"></i>
    </a>
</div>
```

## 🛠️ Troubleshooting

### Common Issues

**1. Website Not Loading**
- Check if all files (index.html, style.css, app.js) are in the same folder
- Ensure file names are exactly correct (case-sensitive)
- Clear browser cache and refresh

**2. Styles Not Working**
- Verify style.css is in the same folder as index.html
- Check for typos in the `<link>` tag in index.html
- Ensure there are no syntax errors in CSS

**3. JavaScript Not Working**
- Check browser console for errors (F12 → Console tab)
- Verify app.js is linked correctly in index.html
- Ensure all JavaScript syntax is correct

**4. Mobile Menu Not Working**
- Check if hamburger button exists in HTML
- Verify JavaScript is loading properly
- Ensure CSS media queries are working

### Getting Help
1. Check browser developer tools (F12) for error messages
2. Validate HTML using [W3C Validator](https://validator.w3.org/)
3. Test CSS using browser inspector tools
4. Use online communities like Stack Overflow for specific issues

## 📊 SEO Optimization

### Meta Tags
**Location:** `index.html`, in `<head>` section

```html
<meta name="description" content="Gokul Kolipaka - Agile Program Manager and Pharma R&D Leader">
<meta name="keywords" content="project manager, agile, pharmaceutical, R&D, consultant">
<meta property="og:title" content="Gokul Kolipaka - Portfolio">
<meta property="og:description" content="Professional portfolio of an experienced project manager">
<meta property="og:image" content="your-photo.jpg">
```

### Google Analytics (Optional)
Add before closing `</head>` tag:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

## 🔄 Regular Updates

### Monthly Updates
- Update current role information
- Add new projects or achievements
- Refresh testimonials or recommendations
- Update skills based on new learning

### Content Strategy
- Keep project descriptions current
- Update metrics and impact numbers
- Add recent certifications or training
- Refresh contact information if needed

## 📋 Checklist Before Going Live

- [ ] All personal information is correct
- [ ] Contact details are up to date
- [ ] All links work properly
- [ ] Website loads on mobile and desktop
- [ ] Images are optimized and load quickly
- [ ] Contact form works (test by sending yourself a message)
- [ ] Navigation menu works on all devices
- [ ] All sections have relevant, accurate content
- [ ] Professional tone throughout
- [ ] No typos or grammatical errors

---

**Need Help?** Remember, web development is iterative. Start with small changes, test frequently, and gradually make bigger customizations as you get more comfortable with the code.
