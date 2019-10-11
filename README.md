# eslint-config-fewlines-ts

Disclaimer: this package is made for our internal usage and is only open source for convenience so we might not consider _Pull Requests_ or _Issues_.

This package includes the shareable ESLint configuration used by Fewlines typescript projects.

Extends `eslint:recommended`, `@typescript-eslint/eslint-recommended`, `@typescript-eslint/recommended`,

## Usage

```shell
yarn add -D @fewlines/eslint-config-fewlines-ts eslint \
eslint-config-prettier eslint-plugin-prettier prettier \
@typecript-eslint/eslint-plugin @typescript-eslint/parser
```


Then add these line to your `package.json`:

```json
"eslintConfig": {
  "extends": "@fewlines/fewlines-ts"
}
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
