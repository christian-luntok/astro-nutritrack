<div align="center">
  <img alt="NutriTrack logo" src="/public/nutritrack.svg" width="100" />
</div>

<h1 align="center">
  Astro NutriTrack - A landing page template 🚀
</h1>

A simple landing page theme built with AstroJS and TailwindCSS, specifically designed for Notion creators. It's easy to customize, allowing you to create a minimalistic site that fits your style using its versatile components.

<hr>

![NutriTrack Mockup](/public/images/nutritrack.png)

## Key Features:

-   Minimal styling (make it your own!)
-   Accessible, semantic HTML markup
-   Blazingly Fast
-   100/100 Lighthouse performance
-   Responsive & SEO-friendly with canonical URLs, OpenGraph data and Meta tags.
-   Sitemap support
-   More than 10+ Components to use!

## Lighthouse Score

NutriTrack scores 100/100 in the Lighthouse performance audit.

![NutriTrack Lighthouse Score](/lighthouse-score.png)

## Demo

Check out the [Demo](https://astro-nutritrack.chrstnl.com/), hosted on Vercel.

## Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## Update Site Metadata

```js
env: {
  siteTitle: 'Your Company',
  siteDescription: 'Your company description.',
  siteKeywords: 'your company keywords',
  siteUrl: 'https://astro-nutritrack.chrstnl.com/',
  siteImagePreviewUrl: '/images/preview.jpeg',
  twitterHandle: '@your_handle'
}
```

## Update Colors

You can update the colors in tailwind.config.js file.

## Update Favicon

Update the manifest.json file and the icons under the public/images/icons folder.

You can use free tools online such as https://realfavicongenerator.net/ to quickly generate all the different icon sizes and favicon.ico file.

## Want to learn more?

Check out [Astro's documentation](https://docs.astro.build).

## Deploy

You can deploy your own Astro site on various platforms by following the [Astro docs](https://docs.astro.build/en/guides/deploy/) guide.

By default, the site will be built (see Commands section above) to a `/dist` directory.

---

Made by [chrstnl](https://chrstnl.com/)
