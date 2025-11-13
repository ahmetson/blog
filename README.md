<h1 align=center>Ahmetson Blog</h1>
<p align=center>A personal blog built with Astro, featuring thoughts, ideas, and articles worth sharing. Built for performance, SEO, and a great reading experience.
</p>
<h2 align="center"> <a target="_blank" href="https://ahmetson.com/" rel="nofollow">🌐 Live Site</a> | <a  target="_blank" href="https://pagespeed.web.dev/report?url=https%3A%2F%2Fahmetson.com%2F&form_factor=desktop">Page Speed🚀</a>
</h2>

<p align=center>
  <a href="https://github.com/withastro/astro/releases/tag/astro%405.14.4" alt="Astro Version">
    <img src="https://img.shields.io/static/v1?label=ASTRO&message=5.14&color=000&logo=astro" />
  </a>
</p>

## 🔑Key Features

- ⚡ Fast by Default - Built with Astro for optimal performance
- 🚀 Vercel Adapter Pre-configured (Node.js adapter for local development)
- ✍️ Write and Update Content in Markdown / MDX
- 📚 MDX Components Auto Import
- 📝 Includes Draft Pages and Posts
- 🎨 Built with Tailwind CSS Framework
- 📱 Fully Responsive on Desktops, Tablets, and Smartphones
- 🔍 SEO Friendly
- 🌅 Support OG Image
- 📬 Contact Form Support

<!-- installation -->

## ⚙️Installation

To set up the blog locally, you'll need to install some prerequisites. You can view the package.json file to see which scripts are included.

### 🔧Install prerequisites (once for a machine)

- **Node Installation:** [Install node js](https://nodejs.org/en/download/) [Recommended LTS version]

### 🖥️Local setup

After successfully installing Node.js, open this project with any IDE [[VS Code](https://code.visualstudio.com/) recommended], and then open the internal terminal of IDE [vs code shortcut <code>ctrl/cmd+\`</code>]

- Install dependencies

```
npm install
```

- Run locally

```
npm run dev
```

After that, it will open up a preview of the blog in your default browser, watch for changes to source files, and live-reload the browser when changes are saved.

**Note:** The project uses Node.js adapter for local development (when `NODE_ENV` is not set to `production`). This allows you to test server-side features locally.

## 🔨Production Build

To create a production build, run this command.

```
npm run build
```

### 🚀 Deployment

The project is configured with adapters that automatically switch based on the `NODE_ENV` environment variable:

- **Development Mode** (default for local): Uses Node.js adapter in standalone mode
  - Automatically used when `NODE_ENV` is not set to `production`
  - Perfect for local development and testing server-side features

- **Production Mode**: Uses Vercel adapter
  - Automatically used when `NODE_ENV=production`
  - Optimized for Vercel deployment

To build for production deployment:

```bash
NODE_ENV=production npm run build
```

For Vercel deployment, the adapter will automatically be set to Vercel during the build process.

## 📄License

Copyright (c) 2025 Medet Ahmetson. All Rights Reserved.

**Code License:** Released under the MIT license.

Built with [Astro](https://astro.build/) and based on the Northendlab Light Astro theme.
