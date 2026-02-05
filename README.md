# Gita Gopinath - Personal Website

A clean, modern personal website built with HTML, CSS, and JavaScript.

## Structure

```
Website/
├── index.html          # Homepage with bio and featured research
├── cv.html             # Curriculum Vitae
├── publications.html   # Research papers and publications
├── speeches.html       # Speeches and keynotes
├── blog.html           # Blog posts
├── media.html          # Media appearances (print, video, podcasts)
├── honors.html         # Honors and awards
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── main.js         # JavaScript functionality
├── images/             # Image assets (add your photos here)
│   ├── gita-gopinath.jpg      # Profile photo
│   ├── dollar-dominance.jpg   # Featured research image 1
│   ├── exchange-rates.jpg     # Featured research image 2
│   └── ipf.jpg                # Featured research image 3
└── files/              # Downloadable files
    └── Gopinath_CV.pdf        # CV PDF file
```

## Setup Instructions

### 1. Add Your Images

Place the following images in the `images/` folder:
- `gita-gopinath.jpg` - Your professional headshot (recommended: 700x700px or similar square format)
- `dollar-dominance.jpg` - Featured research image (recommended: 600x400px)
- `exchange-rates.jpg` - Featured research image
- `ipf.jpg` - Featured research image

### 2. Add Your CV PDF

Create a `files/` folder and add your CV:
```bash
mkdir files
# Copy your CV PDF as Gopinath_CV.pdf
```

### 3. Preview Locally

Simply open `index.html` in your web browser to preview the site.

Or use a local server (recommended):
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then visit `http://localhost:8000`

## Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Push the website files
3. Enable GitHub Pages in repository settings
4. Your site will be available at `https://username.github.io/repository-name`

### Option 2: Netlify (Free)
1. Create a Netlify account
2. Drag and drop the Website folder to deploy
3. Get a free subdomain or connect your custom domain

### Option 3: Custom Domain Hosting
1. Purchase hosting from providers like:
   - Bluehost
   - SiteGround
   - DigitalOcean
   - AWS S3 + CloudFront
2. Upload files via FTP or their dashboard
3. Point your domain to the hosting

## Customization

### Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #1a365d;    /* Dark blue */
    --secondary-color: #2c5282;  /* Medium blue */
    --accent-color: #3182ce;     /* Light blue */
    --text-color: #2d3748;       /* Dark gray */
}
```

### Fonts
The site uses:
- **Inter** - Body text
- **Playfair Display** - Headings

To change fonts, update the Google Fonts link in the HTML files and the CSS variables.

### Content
- Edit the HTML files directly to update content
- Publications, speeches, blog posts, etc. can be added by copying the existing HTML structure

## Features

- Responsive design (mobile-friendly)
- Smooth scrolling
- Animated elements on scroll
- Mobile navigation menu
- Scroll-to-top button
- Clean, professional typography
- Fast loading (no frameworks, minimal dependencies)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This website template is created for Gita Gopinath's personal use.
