# SEP.9 Sushi & Taco — Pikesville, MD

Japanese-Mexican fusion restaurant website. Redesigned Nov 2026.

- Address: 9163 Reisterstown Rd, Pikesville, MD 21208
- Phone: (443) 934-5027
- Hours: Tue–Thu 11:30–21:30, Fri–Sat 11:30–22:00, Sun 12:00–21:00, Mon closed

## Site

`index.html` is a self-contained static site (cream #FAF7F2, nori green
#2C3E35, salmon coral #E06D53): sticky nav, hero "Made with Love. Made to
Share.", three pillars (Sushi Tacos / Signature Rolls / Genki Bento),
searchable menu, 5-step custom builder with live price/nutrition, order
bag with 6% Maryland sales tax, story, visit/hours with live open/closed
status, and footer.

No build step is needed.

## Deploy

- **Vercel:** Import this repository in the Vercel dashboard, framework:
  Other / static, no build command. Add a custom domain later in
  Vercel → Settings → Domains.
- **Netlify:** Drag-and-drop this folder, or connect the repository.
- **GitHub Pages:** Settings → Pages → deploy from the `main` branch.

## Notes

- Menu prices and hours are as shown on the site; confirm with the
  restaurant before publishing a price change.
- Social links in the footer currently point to the platforms' home
  pages; replace them with the restaurant's official handles.
