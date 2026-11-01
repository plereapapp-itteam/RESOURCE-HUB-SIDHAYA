SIDHAYA STUDENT RESOURCE HUB

Deploy this folder as its own Cloudflare Pages project (GitHub repository).

1. Create a separate GitHub repo and upload all files & folders in this directory.
2. In Cloudflare Workers & Pages create a Pages project from this GitHub repo.
3. Before uploading, replace YOUR-ADMIN-PROJECT.pages.dev in index.html with the real admin project's pages.dev domain (or custom domain).
4. The student hub uses the public GET endpoint /api/links?program=sidhaya of the central Admin Pages deployment.
5. Each program gets its own website and does not show a program selection screen.
6. Do not copy schema.sql, admin page, D1 credentials or ADMIN_SECRET to this repository.
7. Deploy admin backend and D1 first; links stay disabled until configured.

Gallery photos and logo are included. Keep gallery/, logos/, and manifest.webmanifest in the repo root.

LOGO FIX: The official program logo is embedded in index.html. No separate logo upload is necessary.
