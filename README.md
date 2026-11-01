# Reusable Webpack 5 Template for VanillaJS

A reusable Webpack 5 template for VanillaJS projects.

## Dependencies

- **html-webpack-plugin** : Used to generate and manage HTML files.
- **css-loader** and **style-loader** : Used to handle CSS imports and inject styles into the DOM.
- **html-loader** : Used to process HTML files and handle assets referenced within them, such as images.

Other dependecies are used for webpack, the development server, linting and formatting.

## Linting

**ESLint** installed as a development dependency for linting. Configuration can be found in _eslint.config.ts_.

## Formatting

**Prettier** installed as a development dependency for formatting. Configuration can found in _.prettierrc_.

**eslint-config-prettier** installed as development dependency to prevent conflicts between **ESLint** and **Prettier**.
