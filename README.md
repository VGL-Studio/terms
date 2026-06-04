# VGL Studio — Terms & Policies

Privacy Policy and Terms of Service pages for VGL Studio apps, hosted on GitHub Pages (Jekyll).

**Live site:** https://vgl-studio.github.io/terms/

## Privacy Policy URLs (copy & paste into store consoles)

```
https://vgl-studio.github.io/terms/diy-wallpaper/privacy
https://vgl-studio.github.io/terms/trending-clicker/privacy
https://vgl-studio.github.io/terms/boomtap-2player/privacy
https://vgl-studio.github.io/terms/hand-control/privacy
```

## All Policy Links

| App | Privacy Policy | Terms of Service |
|-----|----------------|------------------|
| Wallpaper Maker: DIY Collage | https://vgl-studio.github.io/terms/diy-wallpaper/privacy | https://vgl-studio.github.io/terms/diy-wallpaper/terms |
| Trending Clicker | https://vgl-studio.github.io/terms/trending-clicker/privacy | — |
| BoomTap: 2Player | https://vgl-studio.github.io/terms/boomtap-2player/privacy | — |
| Hand Control | https://vgl-studio.github.io/terms/hand-control/privacy | https://vgl-studio.github.io/terms/hand-control/terms |

## Adding a New App

1. Create a folder named after the app slug (e.g. `my-app/`).
2. Add `privacy.md` (and `terms.md` if needed) with this frontmatter:
   ```yaml
   ---
   layout: default
   title: Privacy Policy - My App
   permalink: /my-app/privacy
   ---
   ```
3. Add the links to `index.md` and to this README.
4. Commit and push to `main`; GitHub Pages rebuilds automatically.

The public URL always follows the pattern: `https://vgl-studio.github.io/terms/<slug>/<privacy|terms>`
