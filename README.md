# GH-pages-react-test

create a react app with default:

```bash
npx create-react-app your-app-name
cd your-app-name
npm start
```

install gh-pages

```bash
npm install gh-pages
```

add homepage to `package.json`

```json
    "homepage": "http://{Github-username}.github.io/{Github-repo-name}",
```

add deploy script to `package.json`

```json
    "scripts": {
        "predeploy": "npm run build",
        "deploy": "gh-pages -d build",
    }
```

Now deploy it to GitHub Pages

```bash
npm run deploy
```

`Go to {your-GitHub-code-repository} -> settings -> GitHub pages section and setup source to the gh-pages branch.`

push to git.

```bash
git add .
git commit -m “Your commit message”
git push origin master
```
