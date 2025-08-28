# Power & Pleasure — Mailchimp-only (VIP + Couples)

## How to edit (1–2 lines)
- **Text:** open the relevant `.html` and update copy between tags (e.g., inside `<p>...</p>`). Save, commit, deploy.
- **Images:** upload files to `/assets/` and reference them with `<img src="/assets/yourfile.jpg" alt="..." />`.

## Mailchimp setup
1) Audience → Settings → **Audience fields & *|MERGE|* tags**: create fields `NAMES`, `EVENTDATE`, `BUDGET`, `SIZES`, `PREFS`, `NOTES`.
2) Audience → Signup forms → **Embedded forms** → copy the **form action URL**.
3) In `index.html`, replace `REPLACE_WITH_YOUR_MAILCHIMP_ACTION_VIP` with your action URL (auto-tags **VIP**).
4) In `couples-styling.html`, replace `REPLACE_WITH_YOUR_MAILCHIMP_ACTION_COUPLES` with your action URL (auto-tags **Couples-Styling**). Ensure input names match your merge tags.
5) (Optional) In Mailchimp, enable **signup notifications** so new submissions email the site owner.

## SEO
Pages include `<title>`, `<meta name="description">`, canonical, Open Graph, Twitter Card, plus `robots.txt` and `sitemap.xml`. Update titles/descriptions as needed.
