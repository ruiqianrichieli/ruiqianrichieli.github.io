# Ruiqian (Richie) Li - Academic Portfolio

A clean, professional academic website template built with HTML, CSS, and vanilla JavaScript.

## 🗂️ File Structure

```
lord-richie.github.io/
├── index.html          # Homepage (About, Research, Publications, Contact)
├── cv.html             # Curriculum Vitae page
├── blog.html           # Blog listing page
├── css/
│   └── style.css       # Main stylesheet
├── blog/
│   └── sample-post.html    # Example blog post
├── images/
│   └── headshot.jpg    # Your photo (add this!)
├── files/
│   └── Richie_Li_CV.pdf    # Your CV PDF (add this!)
└── README.md           # This file
```

## 🚀 Quick Start

1. **Clone or download** this repository to your local machine

2. **Add your photo**:
   - Place a professional headshot in `images/headshot.jpg`
   - Recommended size: 400×533px (3:4 aspect ratio)
   - The site will show a placeholder until you add your photo

3. **Add your CV PDF**:
   - Place your CV in `files/Richie_Li_CV.pdf`
   - Update the filename in `cv.html` if you use a different name

4. **Update social links** in `index.html`:
   - Google Scholar ID
   - Bluesky handle
   - ORCID ID

5. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial site setup"
   git push origin main
   ```

6. Your site will be live at `https://lord-richie.github.io`

## ✏️ Customization

### Adding a Blog Post

1. Copy `blog/sample-post.html` to create a new post
2. Update the content, title, date, and meta description
3. Add a new entry in `blog.html` linking to your new post

### Changing Colors

Edit the CSS variables in `css/style.css`:

```css
:root {
  --color-bg: #FDFBF7;           /* Page background */
  --color-primary: #1B3A4B;      /* Headings, logo */
  --color-accent: #C45C3E;       /* Links, highlights */
  --color-text: #2C3E50;         /* Body text */
}
```

### Changing Fonts

The site uses Google Fonts. To change them:

1. Pick fonts from [fonts.google.com](https://fonts.google.com)
2. Update the `<link>` tag in each HTML file's `<head>`
3. Update the CSS variables:

```css
:root {
  --font-display: 'Your Display Font', serif;
  --font-body: 'Your Body Font', sans-serif;
}
```

## 📱 Features

- **Responsive design**: Works on desktop, tablet, and mobile
- **Clean typography**: Libre Baskerville + Source Sans 3
- **Smooth scrolling**: Navigation anchors scroll smoothly
- **Sticky header**: Header stays visible while scrolling
- **Mobile menu**: Hamburger menu for small screens
- **Subtle animations**: Fade-in effects on page load

## 🔧 Technical Notes

- No build tools or dependencies required
- Pure HTML/CSS/JavaScript
- Fast loading (minimal external resources)
- SEO-friendly with proper meta tags
- Accessibility-conscious markup

## 📄 License

Feel free to use and modify this template for your own academic website.

---

Built with care for academic professionals.
