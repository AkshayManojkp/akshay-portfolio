# Akshay Manoj KP — Developer Portfolio

A static, responsive portfolio for **Akshay Manoj KP**, showcasing work across full-stack development, AI products, automation, engineering, and business.

## Live site

After GitHub Pages is enabled and the deployment workflow completes:

- Project site: https://akshaymanojkp.github.io/akshay-portfolio/

> This repository is named `akshay-portfolio`, so GitHub Pages publishes it as a project site under `/akshay-portfolio/`. The root address `https://akshaymanojkp.github.io/` requires a separate repository named exactly `AkshayManojkp.github.io`. The existing `AkshayManojkp` repository is your GitHub profile README repository, so it has intentionally not been renamed or repurposed.

## Stack

- HTML5 for semantic page structure
- CSS for responsive layout, visual system, and animations
- Vanilla JavaScript for interaction and motion
- Three.js r128 for 3D effects (loaded from cdnjs)

No build step is required.

## GitHub Pages setup

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **GitHub Actions** as the source.
3. Open **Actions** and allow workflows if GitHub prompts you.
4. Pushes to `main` will run `.github/workflows/deploy-pages.yml`; you can also run it manually with **Run workflow**.
5. When the workflow succeeds, open the project-site URL above.

The workflow publishes the repository root as a static site. It does not require a package manager or build command.

## Local preview

Run a local static server from the repository root, for example:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Contact and profiles

- GitHub: https://github.com/AkshayManojkp
- LinkedIn: https://www.linkedin.com/in/akshay-manoj-kp/
- Existing Vercel portfolio: https://akshayofficial.vercel.app/

Project and social links in the site point to the public profiles and repositories. Update the relevant links in `index.html` when adding or replacing projects.
