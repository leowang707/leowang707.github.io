# leowang707.github.io

Personal portfolio site for **Wang Chen-Yu (Leo Wang)** — robotics / computer vision engineer.

🔗 **Live site: [https://leowang707.github.io](https://leowang707.github.io)**

## Structure

This is a plain static site (no build step, no Jekyll) based on the [iPortfolio](https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/) Bootstrap template. `.nojekyll` tells GitHub Pages to serve the files as-is.

```
.
├── index.html              # the entire site — one page, sections in order (see below)
├── forms/contact.php        # backend for the contact form (see note below)
└── assets/
    ├── css/style.css        # your custom styles / overrides
    ├── js/main.js            # site behavior (nav, animations, form handling)
    ├── img/                  # your actual photos/icons (profile pic, favicon)
    └── vendor/                # third-party libraries (Bootstrap, AOS, Typed.js, etc.) — don't need to touch these
```

## Editing the content

Everything is in **`index.html`**, split into `<section id="...">` blocks in this order:

| Section | What it is | Line marker to search for |
|---|---|---|
| Hero | Name + rotating title text | `id="hero"` |
| About | Bio, contact details, education | `id="about"` |
| Projects | Project cards (title, description, GitHub link) | `id="projects"` |
| Skills | Skills grouped by category | `id="skills"` |
| Resume | Summary, education, work experience | `id="resume"` |
| Contact | Location, email, phone, map, contact form | `id="contact"` |

To add a new project card, copy one `<div class="col-lg-4 col-md-6 icon-box">...</div>` block inside the Projects section and edit the title/link/description.

To update your profile photo, replace `assets/img/my_profile_img.jpg` (keep the same filename, or update the `src` in the About section of `index.html`).

## Known limitation

The contact form (`forms/contact.php`) requires a PHP-capable server. **GitHub Pages only serves static files and cannot run PHP**, so the form will not currently send email as-is. To make it work, either:
- swap the form's `action` to a static form service (e.g. [Formspree](https://formspree.io/)), or
- remove the contact form and just list your email directly.

## Local preview

No build tools needed — just open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying changes

Commit and push to the `main` branch — GitHub Pages rebuilds automatically within a minute or two.
