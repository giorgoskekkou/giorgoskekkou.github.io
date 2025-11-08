# Personal Portfolio – Giorgos Kekkou

Static personal website showcasing experience, education, research interests, skills, projects, and contact info.

## Features
- Responsive design (HTML5 UP Solid State template)
- Section navigation with hash scrolling
- Projects page with category filtering
- Favicon and profile image
- Mobile-friendly layout adjustments
- Downloadable CV

## Tech Stack
- HTML / CSS / JavaScript
- Template: Solid State by HTML5 UP
- Deployment: GitHub Pages

## Structure
```
assets/
  css/ (main styles)
  js/  (template scripts)
images/ (profile + project images)
projects/ (project detail pages + listing)
files/ (CV, favicon, documents)
index.html (home)
projects/index.html (projects overview)
```

## Getting Started
1. Clone repo:
   git clone https://github.com/giorgoskekkou/giorgoskekkou.github.io
2. Open in VS Code.
3. Use Live Server for local preview.
4. Push to main; GitHub Pages serves automatically.

## Customization
- Edit index.html for content sections.
- Update projects/index.html to add or modify project cards.
- Adjust styles in assets/css/main.css.
- Replace images/profile.jpg for a new avatar.

## Projects Listing
Each project card uses:
```
<article class="project-card" data-category="research">
  <div class="project-meta">Research · 2025</div>
  <h3>Title</h3>
  <p>Short summary.</p>
  <div class="project-tags"><span>Tag</span></div>
</article>
```

## Favicon
Place favicon in files/ and link in head:
```
<link rel="icon" type="image/x-icon" href="files/favicon.ico">
```

## Deployment
- Ensure branch is set in repository settings for GitHub Pages.
- Cache issues: force refresh (Ctrl+F5) after updates.

## Contact
- Email: georgekekkou@gmail.com
- GitHub: https://github.com/giorgoskekkou

## License & Credits
- Template: Solid State by HTML5 UP (CC BY 3.0).
- Icons: Font Awesome.
- Scripts: jQuery, Scrollex, Responsive Tools.
- Images: Replace with your own (ensure rights).
- Your content © Giorgos Kekkou.

