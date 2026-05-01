# Balman Rawat Portfolio

Personal portfolio website for Balman Rawat, Senior DevOps Engineer focused on
AWS, Kubernetes, platform automation, observability, CI/CD, and reliable
production systems.

Live domain: [balmanrawat.com.np](https://balmanrawat.com.np)

## What This Site Contains

- Skills and platform engineering focus areas
- Professional experience
- Certifications
- Community work, talks, teaching, and open-source projects
- External technical writing links
- CV download page

## Tech Stack

- Astro
- Tailwind CSS
- React components where needed
- GitHub Pages deployment

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deployment

The site is deployed with GitHub Actions to GitHub Pages. The custom domain is
kept in `public/CNAME` so it is included in each static build.

## Project Structure

- `src/pages` - custom portfolio pages
- `src/content/homepage` - homepage content
- `src/content/about` - about page content
- `src/content/blog` - external writing index metadata
- `src/config` - site, menu, social, and theme configuration
- `public` - static assets and CV

## License

Website source code is MIT licensed. Personal content, CV, images, and branding
assets are all rights reserved. See [LICENSE](./LICENSE).
