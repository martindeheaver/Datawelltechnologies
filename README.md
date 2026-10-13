# Datawell Technologies Website

Clean, modern static website for [datawelltechnologies.com](https://datawelltechnologies.com).

## Pages

| File | Description |
|------|-------------|
| `index.html` | Homepage – hero, project tiles, About, Contact |
| `cadria.html` | CADRIA.org project page |
| `healthhub.html` | HealthHub project page |
| `datawell.html` | Datawell platform page |
| `paix.html` | PAIX project page |
| `cair.html` | CAIR project page |
| `styles.css` | Shared stylesheet |

## Projects featured

- **CADRIA.org** – Consensus-Anchored Digital Representative Infrastructure for Agents
- **HealthHub** – Android health-data gathering application
- **Datawell** – Core platform & data infrastructure
- **PAIX** – AI project in development
- **CAIR** – Citizen-Centric AI for Resilient IoT Systems (University of Southampton / EPSRC IAA / Innovate UK ICURe Discover)

## Quick start with GitHub Pages

1. Create a new repository on GitHub (e.g. `datawelltechnologies.com` or `datawell-site`).
2. Push this folder to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial site with project pages"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. In the repository settings → **Pages**:
   - Source: Deploy from a branch
   - Branch: `main` / root
4. Point your custom domain `datawelltechnologies.com` to GitHub Pages:
   - Add a CNAME file containing `datawelltechnologies.com`
   - At your domain registrar, create these DNS records:
     - `A` records pointing to GitHub Pages IPs (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153)
     - or a `CNAME` record for `www` pointing to `YOUR_USERNAME.github.io`

## Local preview

Simply open `index.html` in a browser, or run a local server:

```bash
npx serve .
```

## Customisation

- Colours and design tokens live in the `:root` CSS variables in `styles.css`.
- The layout is fully responsive and works well on mobile.
