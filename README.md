# Kevin Malakoff Portfolio

Personal portfolio and open source project showcase built with Astro, Tailwind CSS, and shadcn/ui.

**Live site**: [kmalakoff.github.io](https://kmalakoff.github.io)

## Tech Stack

- [Astro](https://astro.build/) - Static site generator
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS
- [shadcn/ui](https://ui.shadcn.com/) - UI components
- [TypeScript](https://www.typescriptlang.org/) - Type safety

## Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

This site deploys automatically to GitHub Pages via GitHub Actions when pushing to the `master` branch.

## Project Structure

```
/
├── public/
│   └── images/          # Static images
├── src/
│   ├── components/      # Astro components
│   ├── layouts/         # Page layouts
│   ├── pages/           # Route pages
│   └── styles/          # Global styles
├── .github/workflows/   # GitHub Actions
└── astro.config.mjs     # Astro configuration
```
