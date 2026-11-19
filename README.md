# Sami Alhawshabi — Bilingual SEO Portfolio

Static, responsive portfolio with separate English and Arabic URLs.

## Structure
- `/en/` and `/ar/`: localized home pages
- Each language has separate About, Skills, Experience, Projects, and Contact pages
- `sitemap.xml`, `robots.txt`, canonical URLs, reciprocal `hreflang`, Open Graph metadata, and Person structured data

## Before publishing (required)
1. Replace every occurrence of `https://YOUR-DOMAIN.example` in HTML, `sitemap.xml`, and `robots.txt` with the final public site URL (for GitHub Pages, use the exact published URL).
2. Add your real professional email and CV if you want them displayed; the current source did not contain verified contact details or a CV.
3. Add your real portrait if desired; the existing design uses initials rather than a personal photograph.
4. Review project descriptions: they describe solution categories and should not be presented as named client case studies without your approval.
5. Deploy the folder to GitHub Pages or another static host, then submit `/sitemap.xml` in Google Search Console and verify ownership.

## SEO notes
Every language has its own crawlable URL and substantial localized text. Language links are explicit and no automatic language redirect is used. Update canonical and alternate URLs after choosing the final domain. Search visibility and indexing are not guaranteed; Google determines crawling, indexing, and ranking.
