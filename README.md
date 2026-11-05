# Design Portfolio

A professional, responsive portfolio page built for a 99designs graphic-design application.

## Files

- `index.html` — Main portfolio gallery showcasing 30 selected works (image gallery).
- `index-logos.html` — Previous logo-design portfolio (10 hand-crafted logo marks).
- `logos/` — Source SVG + PNG exports for the logo portfolio.

## Customization before publishing

1. Replace `Your Name` in `index.html` (nav brand, `<title>`, footer).
2. Update the email `dailyrecipenest@gmail.com` in the Contact section.
3. Edit the bio in the About section if you want to tweak wording.
4. To add/remove works, edit the `works` array in `index.html`.

## Publishing (for 99designs)

- **Shareable link:** deploy the folder to GitHub Pages, Netlify, Vercel, or any static host — then paste the URL into your 99designs portfolio.
- **Image uploads:** upload the work images as individual portfolio pieces on 99designs.

## Notes

- The page supports light/dark themes (toggle in nav) and is fully responsive.
- Click any work to open a lightbox with prev/next navigation.

## Deploy to Vercel

1. Push this folder to a GitHub repository.
2. Go to https://vercel.com/new and import the repository.
3. Framework preset: "Other" (static). Build command: none. Output directory: `.` (root).
4. Click Deploy. Vercel will give you a live URL — paste it into your 99designs portfolio.

## Deploy to GitHub Pages

1. Push this folder to a GitHub repository.
2. Settings → Pages → Source: Deploy from a branch → `main` / root.
3. Your site will be live at `https://<username>.github.io/<repo>/`.
