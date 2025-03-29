## Getting Started

```sh
# 1. Clone the repository
git clone https://github.com/pederysky/web_astro

cd web_astro

# 2. Install dependencies
npm install

# 3. Run the development server
npm run dev

# 4. Build for production
npm run build

# Deploy the contents of the `./dist` folder wherever you like.
```

## Customization
### Site & Domain Configuration
- Modify `astro.config.mjs` to update your `site` settings, including metadata for SEO.

### Theme Customization
- Adjust the primary theme color in `tailwind.config.js`, to fit your branding.

### Updating Content & SEO
Edit the **Frontmatter** variables in these files:
- `src/layouts/Layout.astro` – General page info (title, SEO, etc.)
- `src/components/Socials.astro` – Update your social media links.
- `src/components/Profile.astro` – Personal profile information.
- `src/components/ContentProjects.astro` – Projects/portfolio section content.
- `src/components/ContentAbout.astro` – About section content.

### Profile Picture
- Replace `/src/assets/profile.png` with your own image.

### Logo & OpenGraph Image
- Update these files:
  - `/public/img/logo.svg` (your logo)
  - `/public/img/meta.png` (your OpenGraph image)

### Sitemap & Robots.txt
- Adjust `/public/robots.txt` to match your domain.

