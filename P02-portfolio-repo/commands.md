# P2 — Portfolio repository with an initial commit

Run these commands inside the portfolio project folder:

```bash
git init
git status
git add .
git commit -m "Initial portfolio structure"
git branch -M main
```

Create an empty repository named `portfolio` on GitHub. Do not initialize it with a README if you already have local files. Then connect and push:

```bash
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git remote -v
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username.

Check the result with `git status` and confirm the files appear on GitHub.
