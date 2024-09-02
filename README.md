# astro-template

An [Astro](https://astro.build/) project template with a few other defaults:

- [Tailwind CSS](https://tailwindcss.com/) for styling and UI
- [TypeScript](https://www.typescriptlang.org/) for type annotations
- [Biome](https://biomejs.dev/) for code linting and formatting

## Quickstart

This repository can be cloned using `degit`:

```sh
# clone `astro-template` into the `my-app` directory
pnpm dlx degit fboulnois/astro-template my-app
```

## Creating this project

> Skip this step. This step was already run and is kept for posterity.

This project was created using [`create astro`](https://docs.astro.build/en/install-and-setup).

The following steps were run to create this project:

```sh
# create a new minimal astro project
pnpm create astro -- --template minimal

# add tailwindcss as an astro plugin
pnpm astro add tailwind

# add biomejs to lint and format code
pnpm add -D @biomejs/biome
```

See the [project history](https://github.com/fboulnois/astro-template/commits/main) for other changes.

## Developing

Install the dependencies using `pnpm install`.

To check the code for issues when developing:

```sh
pnpm lint
pnpm format
pnpm check
pnpm audit
```

To start a development server:

```sh
pnpm dev
```

## Building

To create a production version of the app:

```sh
pnpm build
```

The production build can be previewed with `pnpm preview`.

> To deploy your app, you may need to install an [adapter](https://docs.astro.build/en/guides/integrations-guide/#official-integrations) for your target environment.
