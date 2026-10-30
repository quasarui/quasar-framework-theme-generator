# Repo setup (for the owner)

Steps to publish this repo.

## 1. Create and push

Create the empty public repo `quasarui/quasar-theme-generator` on GitHub (no README, license or .gitignore), then:

```sh
git remote add origin https://github.com/quasarui/quasar-theme-generator.git
git push -u origin main
```

## 2. About box

- **Description:** Free Quasar theme generator: build a Quasar color palette, fonts, icons and dark mode theme with live preview, export for Quasar CLI or Nuxt.
- **Website:** https://www.quasarui.com/tools/theme-builder
- **Topics:** `quasar`, `quasar-framework`, `quasar-theme`, `theme-generator`, `theme-builder`, `color-palette`, `dark-mode`, `vue`, `vuejs`, `nuxt`, `css-variables`, `design-tokens`, `quasarui`

Untick Releases, Packages and Deployments in the About box if you want a clean sidebar.

## 3. GitHub Pages

Settings → Pages → Build and deployment → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.

The page is served at https://quasarui.github.io/quasar-theme-generator/. The canonical link, `og:url` and `og:image` in `index.html` all use that address. If you use a custom domain or a different org or repo name, update those three tags.

## 4. After it is live

- Paste the Pages URL into https://www.opengraph.xyz/ (or the LinkedIn Post Inspector) to check the preview card.
- Link to the repo from somewhere on quasarui.com (for example the Theme Builder or the theming docs) so search engines find it.
