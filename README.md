# Lucas Hints - Web

A simple [svelte](https://svelte.dev/) web application to provide
information over the [Lucas Hints iOS app]().

## Developing

```bash
npm install
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Linting
Prettier is used code formatting, and both Prettier and ESLint are used for linting.

```bash
npm run lint # Lint (no changes)
npm run format # Implements prettier changes
```

## Building

To create a production version of the app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.
