# Ranjith Perera, Justice of the Peace (JP)

Static website for document attestation and certification services. Plain HTML and CSS, no build step.

## Structure

```
.
├── index.html
├── 404.html
├── profile.jpg
├── favicon.svg
├── robots.txt
└── .nojekyll
```

## Publish on GitHub Pages

1. Create a new repository on GitHub, for example `ranjith-perera-jp`.
2. Upload all files in this folder to the repository root, keeping the `assets` folder.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose branch **main** and folder **/ (root)**, then click **Save**.
6. After a minute the site is live at `https://YOUR-USERNAME.github.io/ranjith-perera-jp/`.

To use the address `https://YOUR-USERNAME.github.io/` instead, name the repository `YOUR-USERNAME.github.io`.

## Custom domain (optional)

Add your domain under **Settings > Pages > Custom domain**. GitHub creates a `CNAME` file for you. Then point your domain's DNS records to GitHub Pages as described in the GitHub Pages documentation.

## Editing

- Contact details, address and hours: edit the Contact section and footer in `index.html`.
- Profile photo: replace `profile.jpg`, keeping the same file name.
