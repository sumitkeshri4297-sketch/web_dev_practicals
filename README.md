 # Programming for Web Development – I Laboratory

This repository contains my lab practicals from P1 to P13, arranged module-wise.
Each practical has its own folder so that the work is easy to find and run.

## Modules

### Module 1 – Terminal, Git & GitHub
| Practical | Title |
|---|---|
| P1 | Project folder and terminal navigation |
| P2 | Portfolio repo with an initial commit |
| P3 | Feature-branch Git workflow |
| P4 | GitHub README and version tags |

### Module 2 – HTML & CSS foundations
| Practical | Title |
|---|---|
| P5 | Semantic bio page |
| P6 | Full portfolio page structure in semantic HTML |
| P7 | Design tokens and typography system in CSS |
| P8 | Sticky navbar and card overlay using CSS positioning |
| P9 | Responsive navbar and card grid using Flexbox |

### Module 3 – CSS layout systems
| Practical | Title |
|---|---|
| P10 | Portfolio header and footer with advanced Flexbox |
| P11 | Newspaper-style three-column layout with CSS Grid |
| P12 | Portfolio projects grid with advanced CSS Grid |
| P13 | Choosing between Flexbox and Grid for a shared layout |

## How to run the HTML practicals

1. Open the required practical folder.
2. Open `index.html` in a browser, or use the Live Server extension in VS Code.
3. The stylesheet is linked separately as `style.css`.

## Git commands used in the practicals

### P1 – Project folder and terminal navigation
```bash
pwd
ls
mkdir web-development-lab
cd web-development-lab
mkdir P1 P2 P3 P4
```

### P2 – Portfolio repo with an initial commit
```bash
git init
git status
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/web-development-lab.git
git push -u origin main
```

### P3 – Feature-branch Git workflow
```bash
git switch -c feature/about-section
git status
git add .
git commit -m "Add about section"
git switch main
git merge feature/about-section
git push
```

### P4 – GitHub README and version tags
```bash
git add README.md
git commit -m "Add project README"
git tag -a v1.0 -m "First lab version"
git push origin main
git push origin v1.0
git tag
```

> Replace `YOUR-USERNAME` with your GitHub username before running the remote command.
> Run Git commands from inside the repository folder. The commands above are examples for learning; check `git status` before committing or merging.
