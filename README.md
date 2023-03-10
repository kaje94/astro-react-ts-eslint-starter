# Astro React TypeScript Eslint Starter

![astro-react-ts-eslint-starter](https://socialify.git.ci/kaje94/astro-react-ts-eslint-starter/image?description=1&descriptionEditable=Astro%20starter%20project%20with%20Eslint%20fully%20configured%20for%20React%20%26%20TypeScript&forks=1&issues=1&name=1&owner=1&pattern=Circuit%20Board&stargazers=1&theme=Auto)

The Eslint configurations for react was added on top of the standard Astro empty starter project and therefore it should be pretty straightforward for anyone to port these configurations over to your own project.

## 🪛 Steps to configure

Steps to configure Eslint with your exiting Astro project

1. Copy over the `.eslintrc` and `.eslintignore` files into the root folder of your project.
2. Copy over all of the `devDependencies` found in this project over to your project and install them using either `npm install` or any other alternative approaches that you prefer.
3. Refer the `.vscode/settings.json` to add Eslint related optimizations to VsCode. (Optional).
4. Copy over the `lint` & `lint:fix` scripts from the packages.json over to your project's package.json.
5. Either run `npm run lint` to identify the linting issues or run `npm run lint:fix` to also fix all fixable linting errors.

> Note: This project also includes `Tailwind` specific Eslint configurations.

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
└── .eslintignore
└── .eslintrc
└── .astro.config.mjs
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                                   |
| :--------------------- | :------------------------------------------------------- |
| `npm install`          | Installs dependencies                                    |
| `npm run dev`          | Starts local dev server at `localhost:3000`              |
| `npm run build`        | Build your production site to `./dist/`                  |
| `npm run preview`      | Preview your build locally, before deploying             |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check`         |
| `npm run astro --help` | Get help using the Astro CLI                             |
| `npm run lint`         | <strong>Find Eslint errors</strong>                      |
| `npm run lint:fix`     | <strong>Find and fix all fixable linting errors</strong> |
