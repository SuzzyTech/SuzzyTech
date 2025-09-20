Suzzy Tech — Static Site for suzzytech.site
==========================================

What's inside:
- `index.html` — SEO-optimized landing page (single-page).
- `sitemap.xml` — sitemap for search engines.
- `robots.txt` — robots file.
- `blog/sample-post.html` — example blog post you can expand.
- `_headers` — Vercel headers for security & cache (optional).

How to deploy on Vercel (static site):
1. Go to https://vercel.com and sign in.
2. Click "New Project" → Import from Git (or upload).
   - If you don't use Git, you can simply drag-and-drop this folder to Vercel's dashboard.
3. Vercel will detect static HTML. Deploy.
4. After deploy, go to Vercel's project dashboard → Domains → add `suzzytech.site`.
   - Configure your domain's DNS to point to Vercel (they will give instructions).
5. Open Google Search Console and add `https://suzzytech.site/` as a property, then submit `sitemap.xml`.

SEO Tips included in the project:
- Replace placeholder Imgur links (https://i.imgur.com/PLACEHOLDER-*.jpg) with your real image previews.
- Add more blog posts under `/blog/` with long-form content focused on "WhatsApp bot", "deploy bot", "VPS for bots", etc.
- Create FAQ or HowTo structured-data pages (JSON-LD) for top guides to get rich results.
- Submit site to Google Search Console and request indexing.

Replaceable spots:
- Logo and OG images: `https://i.imgur.com/PLACEHOLDER-logo.png`
- Raganork preview: `https://i.imgur.com/PLACEHOLDER-raganork.jpg`
- OG image: `https://i.imgur.com/PLACEHOLDER-og.jpg`

Good luck — deploy and then tell me when it's live; I'll help push SEO further (keyword plan, blog posts, schema for HowTo/FAQ).
