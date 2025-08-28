# Power & Pleasure — Mailchimp-only (VIP + Couples) with Inline Edit Comments

## How to edit (1–2 lines)
- **Text:** open the relevant `.html` file and update the copy between tags. Inline comments `<!-- like this -->` show safe places to edit.
- **Images:** upload files to `/assets/` and reference them with `<img src="/assets/yourfile.jpg" alt="..." />`.

## Mailchimp setup
1) Audience → Settings → **Audience fields & *|MERGE|* tags**: create fields `NAMES`, `EVENTDATE`, `BUDGET`, `SIZES`, `PREFS`, `NOTES`.
2) Audience → Signup forms → **Embedded forms** → copy the **form action URL**.
3) In `index.html`, replace `REPLACE_WITH_YOUR_MAILCHIMP_ACTION_VIP` (auto-tags **VIP**).
4) In `couples-styling.html`, replace `REPLACE_WITH_YOUR_MAILCHIMP_ACTION_COUPLES` (auto-tags **Couples-Styling**). Keep input `name` attributes unchanged so Mailchimp captures fields correctly.
5) (Optional) Enable **signup notifications** in Mailchimp so new submissions email the site owner.

## SEO
Pages include `<title>`, `<meta name="description">`, canonical, OG/Twitter, plus `robots.txt` and `sitemap.xml`. Update titles/descriptions as needed.
