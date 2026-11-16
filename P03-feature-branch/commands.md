# P3 — Feature-branch Git workflow

```bash
git switch main
git pull origin main
git switch -c feature/about-section
```

Make a change to your portfolio files, then:

```bash
git status
git add .
git commit -m "Add about section"
git push -u origin feature/about-section
```

On GitHub, open a Pull Request from `feature/about-section` into `main`, review it, and merge it. Then update your local main branch:

```bash
git switch main
git pull origin main
git branch -d feature/about-section
```

A branch keeps a feature's work separate until it is ready to merge.
