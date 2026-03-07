---
title: "Understanding the PaperAstro Project Structure"
description: "A walkthrough of the core folders and files that make up the PaperAstro starter template."
pubDate: "Jan 11 2026"
heroImage: "../../assets/scrap-placeholder.png"
---

PaperAstro is designed to be minimal, clear, and easy to extend. This post provides an overview of the project structure so you can quickly understand how the template is organized and where to make changes.

## Key directories

The main folders you will work with include:

### `src/pages/`
This directory contains your site’s routes. Each `.astro` or `.md` file becomes a page on your website.  
Examples include:

- `index.astro` for the homepage  
- `about.astro` for the About page  
- `contact.astro` for the contact form  

### `src/components/`
Reusable UI components such as the header, footer, and utility components live here.  
You can add your own components to keep your layout clean and modular.

### `src/layouts/`
Layouts define the structure shared across multiple pages.  
For example, `BlogPost.astro` controls how individual blog posts are displayed.

### `src/content/blog/`
This folder contains your Markdown or MDX blog posts.  
Each post includes frontmatter metadata such as:

- `title`
- `description`
- `pubDate`
- `heroImage`

## Assets and styling

### `src/assets/`
Images, hero graphics, and other static assets are stored here.  
Astro’s image optimization pipeline ensures they are responsive and efficient.

### PaperCSS styling
PaperAstro uses PaperCSS for all styling. No custom CSS is required, but you can extend the design by adding your own styles if needed.

## Configuration files

### `astro.config.mjs`
Controls Astro integrations, build settings, and site configuration.

### `src/consts.ts`
Stores global constants such as the site title and description.

## Extending the template

PaperAstro is intentionally minimal, giving you the freedom to:

- Add new pages  
- Create custom layouts  
- Integrate additional Astro features  
- Expand the blog section  
- Introduce new components  

The structure is designed to stay out of your way while providing a solid foundation for content‑driven websites.

## Summary

Understanding the project structure is the first step toward customizing PaperAstro for your needs.  
With a clear layout and minimal overhead, you can quickly build a site that is both functional and visually distinctive.

