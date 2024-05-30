# Biome configuration based on Standard

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](https://commitizen-tools.github.io/commitizen/)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg?style=flat-square)](https://conventionalcommits.org)
[![lefthook](https://img.shields.io/badge/lefthook-enabled-rgb(208%2C80%2C48)?style=flat-square)](https://github.com/evilmartians/lefthook)

A port of the StandardJS ESLint configuration to Biome.

## Installation / Getting Started

Run the following command to install the Biome configuration:

```bash
npm install git+ssh://git@github.com:robinwalterfit/biome-standard.git#v0.1.0
```

Then add to your Biome configuration:

```jsonc
{
	"$schema": "https://biomejs.dev/schemas/1.7.3/schema.json",
	"extends": ["biome-standard/biome"],
	// ... your individual configuration
}
```

## Deployment

Currently, this package is not published on any registry. Follow the [installation instructions](#installation--getting-started),
if you want to use this Biome configuration.

## Development

Developing Biome Standard configuration is very simple. Biome names their rules
differently from ESLint, but thankfully the Biome CLI provides a migration
command. In order migrate a StandardJS configuration to Biome, all you have to
do is to run the following command.

```bash
biome migrate eslint --include-inspired --include-nursery --write
```

Note however, that migrate will search for a typical `.eslintrc` file. It's not
possible to provide multiple files as input. Fortunately, multiple calls to
`biome migrate` will end up in merging the exisiting biome configuration with
the new rules. The next section will tell you what StandardJS configuration was
used to generate this Biome configuration.

### Dependencies

Run

```bash
npm install --save-dev eslint-config-love@51.0.1 eslint-config-standard@17.1.0 eslint-config-standard-jsx@11.0.0 eslint-config-standard-react@13.0.0
```

and find the packages in `node_modules`. Copy the ESLint configuration to the
root directory, name it `.eslintrc.json` and run `biome migrate` one by one.

**NOTE**: `eslint-config-love` won't export a typical `.eslintrc` configuration
file. Instead you will find a `index.js`. Copy this file and name it `.eslintrc.cjs`.

## Links

- Biome configuration based on Standard: [https://github.com/robinwalterfit/biome-standard](https://github.com/robinwalterfit/biome-standard)
- Issue tracker: [https://github.com/robinwalterfit/biome-standard/issues](https://github.com/robinwalterfit/biome-standard/issues)
- More Links:
  - Biome repository: [https://github.com/biomejs/biome](https://github.com/biomejs/biome)
  - Collection of useful `.gitattributes` templates: [https://github.com/gitattributes/gitattributes](https://github.com/gitattributes/gitattributes)
  - Commitizen: [https://commitizen-tools.github.io/commitizen/](https://commitizen-tools.github.io/commitizen/)
  - Conventional Commits: [https://www.conventionalcommits.org/en/v1.0.0/](https://www.conventionalcommits.org/en/v1.0.0/)
  - EditorConfig: [https://editorconfig.org/](https://editorconfig.org/)
  - `.gitignore` Generator: [https://gitignore.io](https://gitignore.io)
  - Lefthook: [https://github.com/evilmartians/lefthook](https://github.com/evilmartians/lefthook)
  - StandardJS: [https://standardjs.com/](https://standardjs.com/)
    - `eslint-config-love@51.0.1`: [https://github.com/mightyiam/eslint-config-love/tree/v51.0.1](https://github.com/mightyiam/eslint-config-love/tree/v51.0.1)
    - `eslint-config-standard@17.1.0`: [https://github.com/standard/eslint-config-standard/tree/v17.1.0](https://github.com/standard/eslint-config-standard/tree/v17.1.0)
    - `eslint-config-standard-jsx@11.0.0`: [https://github.com/standard/eslint-config-standard-jsx/tree/v11.0.0](https://github.com/standard/eslint-config-standard-jsx/tree/v11.0.0)
    - `eslint-config-standard-react@13.0.0`: [https://github.com/standard/eslint-config-standard-react/tree/v13.0.0](https://github.com/standard/eslint-config-standard-react/tree/v13.0.0)
  - Visual Studio Code: [https://code.visualstudio.com/](https://code.visualstudio.com/)
