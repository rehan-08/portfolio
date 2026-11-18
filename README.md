# Rehan Mhate — Portfolio

A static, responsive portfolio site for GitHub Pages. It uses HTML, CSS, and vanilla JavaScript; no build step or backend is required.

## Files
- `index.html` — website source
- `earth-hero.jpg` — realistic Earth artwork used in the landing page
- `Rehan_Mhate_Resume.pdf` — resume linked from the navigation and hero
- `.nojekyll` — GitHub Pages helper

## Publish at https://rehan-08.github.io/
1. Create a public GitHub repository named exactly `rehan-08.github.io` (or use your existing one).
2. Upload all four files above into the repository root, keeping the filenames unchanged.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, branch `main`, folder `/(root)`, then save.
5. Wait for the first deployment, then open `https://rehan-08.github.io/`.

If you use Git locally, clone your repository first, copy the four files into its root, then run:
```bash
git add index.html earth-hero.jpg Rehan_Mhate_Resume.pdf .nojekyll
git commit -m "Update portfolio website"
git push origin main
```

## Configured profiles
- Email: `rehanmhate@gmail.com`
- GitHub: `https://github.com/rehan-08`
- LinkedIn: `https://www.linkedin.com/in/rehanmhate08/`

## Notes
- Keep `earth-hero.jpg` beside `index.html`; the landing page references it with a relative path.
- Keep the resume PDF beside `index.html`; the Resume link references it with a relative path.
- The contact form opens the visitor's email application with a prefilled message. It does not send or store messages on a server.
- Project repository links are intentionally omitted until supplied.
- Review project summaries and skill lists before publishing to ensure they reflect your current implementation and experience.
