# Aung Thu Hein Oo — Premium Cloud / FinOps Portfolio

A recruiter-focused, responsive static portfolio based on the supplied 2026 CV and FinOps cover letter.

## Features
- Premium dark cloud/enterprise visual system
- Responsive desktop/tablet/mobile design
- Animated architecture diagram
- Real technology logos via Simple Icons CDN
- Dedicated case-study pages:
  - FinOps optimization
  - AKS public/private migration
  - Enterprise reliability
- Downloadable CV and FinOps cover letter
- English / German language toggle
- Recruiter snapshot and quantified outcomes
- GitHub Pages-ready static architecture
- No backend required

## Run locally

```bash
python -m http.server 8000
```

Open http://localhost:8000

## GitHub Pages

This is a static site and can be deployed directly through GitHub Pages. GitHub's documentation supports publishing static HTML/CSS/JS from a repository.

For a user site, create `<your-github-username>.github.io`, push this repository, then enable Pages under Settings → Pages.

## Important

The technology logo cards use the Simple Icons CDN. If you want a completely offline/self-contained version, download the SVG assets and place them under `assets/icons/`, then replace the CDN URLs in `index.html`.

## Content integrity

Portfolio claims are intentionally limited to information documented in the supplied CV and cover letter. No undocumented client metrics or architecture details have been invented.
