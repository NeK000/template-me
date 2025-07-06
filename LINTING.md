# Linting and Formatting

This project uses the following tools for code quality:

- **stylelint**: CSS linter and formatter (with standard config)
- **htmlhint**: HTML linter for Hugo templates

## Usage

Install dependencies:

```sh
npm install
```

Run all linters:

```sh
npm run lint
```

Or run individually:

```sh
npm run lint:css    # Lint CSS
npm run lint:html   # Lint HTML
```

You can adjust rules in `stylelint.config.js` and `.htmlhintrc` as needed.
