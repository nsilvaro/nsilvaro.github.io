# Website for GitHub Pages

The public pages the App Store needs. Copy the contents of this folder (including `.nojekyll`) into a **separate public repository**
named `<your-github-username>.github.io` (for this account: `nsilvaro.github.io`), so the pages are served at the root of
`https://nsilvaro.github.io/`. Do not publish the game's own repository: its `docs/` folder holds internal notes.

| File                       | Address after publishing                              | Use                                             |
| -------------------------- | ----------------------------------------------------- | ----------------------------------------------- |
| `index.html`               | `https://nsilvaro.github.io/`                         | the studio page (the "Marketing URL")           |
| `infiniterun/privacy.html` | `https://nsilvaro.github.io/infiniterun/privacy.html` | Privacy Policy URL in App Store Connect         |
| `infiniterun/support.html` | `https://nsilvaro.github.io/infiniterun/support.html` | Support URL in App Store Connect                |
| `app-ads.txt`              | `https://nsilvaro.github.io/app-ads.txt`              | AdMob verification (must be at the domain root) |

Steps are in `todo.md` ("Host the privacy policy and support page").
