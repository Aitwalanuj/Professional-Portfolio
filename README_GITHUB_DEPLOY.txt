GitHub Pages only package

Upload/commit these files directly to the root of your GitHub repository:

- index.html
- site-data.default.json
- .nojekyll

Do not upload Netlify files such as netlify.toml, package.json, .env.example, or _redirects for GitHub Pages.

After committing, go to GitHub repo Settings > Pages and set:
Source: Deploy from a branch
Branch: main
Folder: / (root)

Your GitHub Pages URL should then show the same portfolio content as Netlify.
