# P4 — GitHub README and version tags

Create a `README.md` in the project root. A sample README is provided at the root of this pack. Adapt it to your own portfolio.

After editing and committing the README:

```bash
git add README.md
git commit -m "Add project README"
git push
```

Create a version tag:

```bash
git tag -a v1.0.0 -m "First portfolio release"
git push origin v1.0.0
```

Useful checks:

```bash
git tag
git show v1.0.0
```

To publish all local tags at once, use `git push --tags`.
