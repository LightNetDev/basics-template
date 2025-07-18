# Basics Template

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/lightnetdev/basics-template)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/lightnetdev/basics-template)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Flightnetdev%2Fbasics-template&env=MY_KEY)

A minimal LightNet starter with the core structure and configuration, ideal for developers who want full control or to deeply customize.

View it online at [sk8-ministries.pages.dev](https://sk8-ministries.pages.dev/).

Use this example to explore how to build a LightNet site or as a starting point for your own site. To **create a local copy**, run the following from your terminal:

```sh
npm create astro@latest -- --template LightNetDev/basics-template
```

## 🚀 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 🖥️ Admin UI

To run the Admin UI locally, execute `npm run dev` and then `npx decap-server` from a second terminal tab from the root of the project.
After this, navigate your browser to [localhost:4321/admin](localhost:4321/admin) and start administrating your content.

When "publishing" your changes they will be saved to your computer's disk only.
