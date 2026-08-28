# svenska-site

The public pages for the **Svenska** iOS app: privacy policy, terms of use and
support. Served by GitHub Pages at
<https://0quantum.github.io/svenska-site/>.

The App Store listing and the app itself link straight here, so these paths are
load-bearing — do not rename a file without changing `src/link.js` in the app:

| Page | Linked from |
|---|---|
| `privacy.html` | App Store Connect, and Settings → Privacy Policy |
| `terms.html` | App Store Connect, and Settings → Terms of Use |
| `support.html` | App Store Connect support URL |

Plain HTML and one stylesheet, no build step. Edit and push; Pages redeploys.

Sibling of [suomi-site](https://github.com/0quantum/suomi-site), which serves the
same three pages for the Finnish app.
