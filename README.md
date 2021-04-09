# GH-pages-react-test

```bash
npx create-react-app your-app-name
cd your-app-name
npm start
```

install

```
npm install gh-pages
```

```json
    "homepage": "http://{Github-username}.github.io/{Github-repo-name}",
```

```json
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
  }
```

Go to {your-GitHub-code-repository} -> settings -> GitHub pages section and setup source to the gh-pages branch.
