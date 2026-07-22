# AstraSure Public Website

Static public website for `astrasure.in`. No build step is required.

## Preview

From this directory:

```sh
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## GitHub Pages

1. Publish this directory at the root of a repository or copy its contents into a repository's `docs` directory.
2. In GitHub, open **Settings > Pages** and select the branch and folder containing this site.
3. Add the four GitHub Pages `A` records at the domain provider and point `www` to the repository's GitHub Pages hostname with a `CNAME` record.
4. In GitHub Pages settings, set the custom domain to `astrasure.in` and enable HTTPS after DNS verification.

The included `CNAME` file preserves the custom domain during deployment.

## Before Launch

- Confirm that `hello@astrasure.in` is configured, or replace it in `index.html`.
- Replace the portfolio image as customer-approved pilot evidence becomes available.
- Keep detailed workflow diagrams, internal model logs, customer-owned material and implementation documentation out of this public folder.

## Public Asset Policy

The website intentionally contains only a high-level portfolio screenshot and an original editorial hero image. Detailed workflow screens and the internal assurance flow are excluded from the deployable package.
