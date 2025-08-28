# Power & Pleasure — Marketing Site

## How to edit (1–2 lines)
- **Text:** open the relevant `.html` file and change the copy between the tags (e.g., inside `<p>...</p>`). Save, commit, deploy.
- **Images:** place files in `/assets/` and reference them with `<img src="/assets/yourfile.jpg" alt="..." />`.

## VIP (Mailchimp)
Mailchimp → Audience → Signup forms → **Embedded forms** → copy the **form action URL** and replace it in the VIP form’s `action` attribute in `index.html`.

## Couples-Styling Form
- **Netlify hosting:** already configured (uses `data-netlify="true"`). Submissions appear in Netlify Forms.
- **Other hosting:** use Formspree (free tier). Create a form and replace the `action="https://formspree.io/f/REPLACE_ID"` in the commented section of `couples-styling.html`.

## SEO
Each page has `<title>` + `<meta name="description">`, canonical, Open Graph, Twitter Card, plus `robots.txt` and `sitemap.xml`. Update titles and descriptions as needed.
