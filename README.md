
# Property DNA - GitHub Pages Deployment

To run locally:
```bash
npm install
npm start
```

To deploy to GitHub Pages:
1. Set "homepage" in package.json to: "https://yourusername.github.io/repo-name"
2. Install gh-pages: `npm install gh-pages`
3. Add scripts:
```json
"predeploy": "npm run build",
"deploy": "gh-pages -d build"
```
4. Run `npm run deploy`
