# nomadka.github.io

Personal portfolio of **Noushiq Kayilan** — computer vision engineer working on perception for LLM-based autonomous driving, 3D geometry, and applied computer vision.

**Live site:** [https://nomadka.github.io](https://nomadka.github.io)

## What is here

- Four case studies: TLS-Assist, wood surface defect detection, point-cloud alignment, and a camera calibration toolkit.
- A research page for the IEEE IV 2026 paper *Enhancing LLM-based Autonomous Driving with Modular Traffic Light and Sign Recognition*.
- An about page and a contact route.

The site is static, has no cookies or trackers, and is built from verified project material. Where real metrics were unavailable, the limitation is stated rather than filled in with a fictional number.

## Stack

- [Astro](https://astro.build/) with TypeScript
- Custom CSS (no UI framework)
- Instrument Serif, Geist, and JetBrains Mono via Fontsource
- GitHub Actions → GitHub Pages

## Local development

```bash
npm install
npm run dev
```

Open `http://localhost:4321`.

Build and preview the production output:

```bash
npm run build
npm run preview
```

## Structure

```text
src/
  components/    navigation, footer, case-study shell, project cards
  layouts/       base layout and case-study layout
  pages/         home, work index, four case studies, research, about, 404
  styles/        design tokens and shared case-study styles
public/
  images/        project imagery and generated verification figures
  favicon.svg
  robots.txt
  sitemap.xml
```

Local research material used to write the case studies lives in `_review/` and is intentionally ignored by Git.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and deploys the `dist/` artifact to GitHub Pages. The repository's Pages source must be set to **GitHub Actions**.

## Contact

- Email: [noushikayilan@gmail.com](mailto:noushikayilan@gmail.com)
- GitHub: [@nomadka](https://github.com/nomadka)
- LinkedIn: [in/noushiq](https://www.linkedin.com/in/noushiq)
