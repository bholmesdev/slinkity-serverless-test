---
title: Deployment
layout: layout
permalink:
  possum: '/deployment/'
---

Slinkity projects can be hosted with the same `build` command and `publish` directory on any of the common Jamstack hosting providers such as [Netlify](https://ajcwebdev-slinkity.netlify.app/), [Vercel](https://ajcwebdev-slinkity.vercel.app/), or [Cloudflare Pages](https://ajcwebdev-slinkity.pages.dev/). All three of these options allow you to create a custom domain name as well.

### Deploy to Netlify

{% component 'Slinky.svelte', hydrate=true %}

The `netlify.toml` file includes `npx slinkity` for the build command and `_site` for the publish directory.

```toml
[build]
  command = "npx slinkity"
  publish = "_site"
```
