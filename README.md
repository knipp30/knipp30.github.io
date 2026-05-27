# Red Hat Learning Hub
Comprehensive guides and exam preparation for Red Hat technologies.

## Sections
- **RHEL 10** — Practical guides for modern Linux infrastructure
- **RHOAI EX267** — Exam prep for Red Hat Certified Specialist in OpenShift AI Self-Managed

## Deployment

This site uses GitHub Pages. Push to the `main` branch of the `rhoai-ex267.github.io` (or configured) repository to deploy.

### GitHub Pages Setup
1. Push to GitHub
2. Go to Settings > Pages > Source > Deploy from a branch
3. Select `main` branch and `/ (root)`
4. Site will be available at `https://yourusername.github.io/`

### Branch strategy
Use a `site/` branch if you want the root of the repo as the GitHub Pages source.

## Structure
```
.
├── index.html              # Main landing page
├── css/
│   └── style.css           # Shared styles
├── rhel/                   # RHEL 10 guides
├── rhoai-ex267/           # RHOAI EX267 exam prep
└── .gitignore
```
