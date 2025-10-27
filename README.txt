
WD4E Accessible Website Starter
================================

Files:
- index.html        (Skip link, Flex navbar, Grid hero)
- gallery.html      (At least 6 images, Grid layout, :hover + :nth-child demos)
- about.html        (Checklist, tips, Flex navbar)
- styles.css        (Global styles, Skip link focus, Flex + Grid, Box model on images)

Meets requirements:
- Skip to main content link shown only on :focus (positioned off-screen by default)
- Accessible, appealing navigation (flex, hover, focus-visible)
- Effective use of grid (hero and gallery) and flex (navbar)
- Box model on all images: border, padding, border-radius
- :hover effect and :nth-child() example
- Validate with W3C and WAVE

How to validate:
- Open https://validator.w3.org/ and paste your page URL or upload files
- Open https://wave.webaim.org/ and enter deployed URL

Deployment options:
- GitHub Pages: push files, enable Pages
- Netlify: drag-and-drop the folder
- Replit: create static HTML/CSS project and upload files

Tips to avoid common errors:
- Link the same styles.css on all three pages
- Close braces and semicolons in CSS rules
- Use aria-current="page" for current nav item
- Ensure image alt text is meaningful and concise
