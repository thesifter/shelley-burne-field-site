# Shelley Burne-Field Author Site Prototype

Static HTML/CSS prototype for a GitHub Pages author website. This is a prototype only, not a production system.

The site is intended to feel like Shelley's own place on the internet: literary, readable, easy to publish, community-oriented, a little off-centre, and light enough to host directly on GitHub Pages.

## Prototype Status

This is an exploratory design prototype. It is meant to help evaluate tone, structure, page flow, and visual direction before any production decisions are made.

It is not:

- a production website
- a CMS
- an ecommerce system
- a private document library
- a source of verified biography or bibliography content
- a final brand identity

## Process So Far

The prototype was created in a deliberately lightweight way:

1. Built a plain HTML/CSS GitHub Pages-compatible site with no framework, no build tooling, and no backend.
2. Created the requested page set: home, writing, books, library, about, and contact.
3. Used clearly marked placeholder content throughout, avoiding invented biographical details and avoiding scraped or copyrighted book imagery.
4. Started with a soft literary layout, then reviewed it in a local browser.
5. Adjusted the visual direction after review because the first version felt too plain and too safe.
6. Tried a more angular editorial/zine direction with stronger cards, bolder borders, and brighter colour.
7. Refined again after browser review: kept the card structure and editorial contrast, removed the math-paper grid effect, and replaced loud colours with a more restrained print-like palette.

The current direction is intended to be distinctive without becoming corporate or startup-like: structured cards, readable typography, visible handmade edges, muted colour, and enough contrast to feel alive.

## Files

- `index.html` - home page with latest writing first
- `writing.html` - placeholder writing index
- `books.html` - placeholder book cards, cover blocks, ISBN fields, publisher links, and buy links
- `library.html` - visual-only archive and document-library mockup
- `about.html` - placeholder biography page
- `contact.html` - placeholder contact, school visits, and speaking page
- `styles.css` - shared responsive styling
- `.nojekyll` - tells GitHub Pages not to run Jekyll processing

## Important Content Notes

- All content is placeholder.
- No biographical facts have been invented.
- No copyrighted book images have been scraped or included.
- Replace placeholder emails, links, book titles, ISBNs, publisher links, and biography text before any real publication.
- The library page is visual only and does not provide private drafts, authentication, syncing, search, or CMS behaviour.
- Book cover blocks are CSS placeholders, not representations of real books.
- External buy links, publisher links, and email addresses are placeholders.

## Local Preview

You can open `index.html` directly in a browser.

If you prefer a local web server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Initial Git Setup Commands

Run these from the project folder:

```bash
git init
git add index.html writing.html books.html library.html about.html contact.html styles.css README.md .nojekyll
git commit -m "Create static author site prototype"
```

This prototype was prepared locally with the same shape of commands. If the repository has already been initialised, use:

```bash
git status
git add .
git commit -m "Refine static author site prototype"
```

Create a new GitHub repository, then connect and push:

```bash
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

## GitHub Pages Deployment

1. Open the repository on GitHub.
2. Go to **Settings**.
3. Open **Pages** in the left sidebar.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Set the branch to `main`.
6. Set the folder to `/root`.
7. Save.

GitHub will publish the site at a URL similar to:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

If using a custom domain later, configure it from the same **Pages** settings screen.

## Suggested Release Notes

For an initial prototype release:

```text
v0.1.0 - Static author site prototype

- Adds a GitHub Pages-compatible static HTML/CSS prototype.
- Adds home, writing, books, library, about, and contact pages.
- Prioritises latest writing and simple publishing paths.
- Uses placeholder-only content and CSS placeholder book covers.
- Includes a visual-only library/archive concept.
- Establishes a restrained literary editorial style for review.
```

## Prototype Boundaries

This project intentionally avoids:

- frameworks
- build steps
- CMS integration
- backend code
- ecommerce
- scraped images
- contact form processing
- production publishing workflows

The next useful step would be to replace placeholders with approved text and real image assets supplied by the author or publisher.
