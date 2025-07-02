# Portfolio

This repository contains the source code of my personal portfolio. It is built with **Astro** and uses **React** components along with **Tailwind CSS** for styling. The site is deployed on Vercel.

## Installation

```bash
npm install
```

## Development

Start the development server with:

```bash
npm run dev
```

## Deployment

Generate the static files with:

```bash
npm run build
```

Upload the contents of the `dist/` folder to any static hosting provider or connect this project to Vercel for automatic deployments.

## Project structure

- **src/** contains all the source code.
  - **pages/** includes the main pages of the site.
  - **layouts/** defines the base template.
  - **components/** groups the reusable components for each section (home, projects, experience, etc.).
  - **styles/** stores global styles.
- **public/** holds images, certificates, and other static files.
- **astro.config.mjs** configures Astro with the Tailwind and React integrations.
- **package.json** declares the project dependencies and scripts.

## Technologies

- [Astro](https://astro.build/) for static site generation.
- [React](https://reactjs.org/) for interactive components.
- [Tailwind CSS](https://tailwindcss.com/) for styling.
- [Vercel](https://vercel.com/) for deployment and traffic analytics.

## License

This project is licensed under the [MIT License](LICENSE).
