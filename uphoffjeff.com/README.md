# uphoffjeff.com

Static one-page site prepared for GitHub Pages with a custom domain.

## Included

- `index.html` for the full landing page
- `styles.css` for all styling
- `assets/covers/` with extracted book covers
- `assets/books/` with downloadable EPUB files
- `CNAME` set to `uphoffjeff.com`
- `.nojekyll` so GitHub Pages serves the site as plain static files

## Publish on GitHub Pages

1. Create a GitHub repository, or use an existing one for the site.
2. Upload the files in this folder to the repository root.
3. In GitHub, open `Settings` > `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select your default branch and `/ (root)`, then save.
6. Wait for the first deployment to finish.

## Connect the custom domain

In your DNS provider for `uphoffjeff.com`, point the apex domain to GitHub Pages using A records:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Optional: add a `www` CNAME pointing to `<your-github-username>.github.io`.

## Notes

- Replace the contact email in `index.html` with your preferred address.
- The book titles came from the EPUB metadata; if you want nicer display names for The Observer volumes, edit those headings directly in `index.html`.
