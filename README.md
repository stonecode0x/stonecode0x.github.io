# StoneCode

Source for the StoneCode website, hosted on GitHub Pages at **[stonecode0x.dev](https://stonecode0x.dev/)**.

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | The landing page (single self-contained HTML file with inline CSS) |
| `CNAME` | Custom domain for GitHub Pages (`stonecode0x.dev`) |
| `robots.txt` | Crawler rules and sitemap location |
| `sitemap.xml` | Sitemap for search engines |

## Local preview

No build step is required. Open `index.html` directly in a browser, or serve the directory:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deployment

Pushing to `main` publishes the site automatically via GitHub Pages.

When updating page content, also bump `<lastmod>` in `sitemap.xml`.

## Contact

[contact@stonecode0x.dev](mailto:contact@stonecode0x.dev)
