# Minimalist Astro Blog

A high-performance, minimalist blog focused on technology and productivity, built with [Astro](https://astro.build) and [Tailwind CSS v4](https://tailwindcss.com/).

## 🌟 Features

- **Blazing Fast**: Built with Astro for optimal performance and zero JavaScript by default.
- **Modern Styling**: Styled with Tailwind CSS v4 for a clean, highly readable, and responsive design.
- **Content-First**: Markdown-powered blog posts leveraging Astro's Content Collections for type safety.
- **Clean Typography**: Focus on extreme readability and modern aesthetics.
- **Automated Deployments**: Configured with GitHub Actions for seamless CI/CD.

## 🚀 Project Structure

```text
/
├── public/          # Static assets (images, fonts, etc.)
├── src/
│   ├── components/  # Reusable UI components
│   ├── content/     # Blog posts (Markdown/MDX)
│   ├── layouts/     # Page layouts
│   └── pages/       # Routing (Index, Blog List, Post View)
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm run dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm run build`           | Build your production site to `./dist/`          |
| `pnpm run preview`         | Preview your build locally, before deploying     |
| `pnpm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro -- --help` | Get help using the Astro CLI                     |

## 🛠️ Technology Stack

- **Framework**: [Astro 6.1+](https://astro.build/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Package Manager**: [pnpm](https://pnpm.io/)
