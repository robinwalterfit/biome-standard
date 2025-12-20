# Biome configuration based on Standard

[![Checked with Biome](https://img.shields.io/badge/Checked_with-Biome-60a5fa?style=flat-square&logo=biome)](https://biomejs.dev)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4BAAAA.svg?style=flat-square)](./.github/CODE_OF_CONDUCT.md)
[![Conventional Branch](https://img.shields.io/badge/Conventional%20Branch-1.0.0-blue.svg?style=flat-square)](https://conventional-branch.github.io/)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg?style=flat-square)](https://conventionalcommits.org)
[![lefthook](https://img.shields.io/badge/lefthook-enabled-brightgreen?logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nNDAwJyBoZWlnaHQ9JzI3MicgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJz48cGF0aCBmaWxsPScjRkYxRTFFJyBkPSdNMjU4IDI2Mi42TDE0OSAyMTBsLTcyLjQgMjIuM0w1IDE5Ny44bDc2LjctOTguNC0xMy4xLTI0LjVMMTEwLjggMzZsNjUuNC0yLjdMMjUxLjkgNSAzODYuNyAxNTAgMzIzIDI0Ni42eicvPjxwYXRoIGQ9J004My4yIDE2Ni44YzI4LjYgOC42IDU4LjUuNiA4OS45LTI0LjFsMTQ3IDk1LjItMzAgMTguNWgtNDlsLTc3LjUtMzguMi03MC44IDE4LTgwLjQtMzYuNkw2OS43IDE3MGwxMy41LTMuMnptNTItMTEyLjdjMTAuMy0yLjcgMzEuNyAyMi4zIDMyLjcgMjguNCAzLjggMjEuMiA1LjQgMzUuNS0yMC43IDU2LjRhNjkuOCA2OS44IDAgMCAxLTU2LjUgMTUuN2w1LjItMjMuM0w3NyA5My43YTk2LjYgOTYuNiAwIDAgMSA1OC4xLTM5LjZ6JyBmaWxsPScjQkYwMDAwJy8+PHBhdGggZD0nTTkwLjUgMjQzLjZsLTEuNy41TC4zIDIwNC4zbDItNC41YzE0LjEtMzIuNiAzNS02MS4yIDYyLjMtODUuOGEzNjAuNiAzNjAuNiAwIDAgMSAxMS44LTEwLjJsLTQuNi04LjctNS42LTEwLjUtMS44LTMuNS0xLjItMi4zIDEuMS0yLjNjMTIuMy0yNSAzMS41LTM5IDYyLjgtNDcuNSAxOS4xLTUgMzUuMS00LjcgNDggMS40QTI4Ny42IDI4Ny42IDAgMCAxIDI1MS4zLjdsMS0uMiAxNDQuNSAxNTUtMS42IDNhMzE4NCAzMTg0IDAgMCAxLTM3LjQgNzIuNmMtMTcuMyAzMi42LTQ2IDQ0LjQtODMuMyAzOS0yOC00LTU4LjUtMTctOTUtMzcuOGwtMTEtNi4xYy0xNi45IDIuNS00MyA4LjMtNzguMSAxNy40ek03MS4yIDEyMS41YTIzNy4yIDIzNy4yIDAgMCAwLTU3LjcgNzcuN2w2MS4yIDI3LjZhNTE3LjUgNTE3LjUgMCAwIDEgNjIuNS0xOC4zIDI3MjQ0LjggMjcyNDQuOCAwIDAgMC02My42LTM1LjZsLTQuNi0yLjYgMjMuMy0zNi41LTExLjEtMjFhMzUxLjIgMzUxLjIgMCAwIDAtMTAgOC43em0zNy4yIDQ4LjZoLjFjMzcuOC02LjcgNjcuNC0zNi43IDc4LTU1LjdhMjE0LjIgMjE0LjIgMCAwIDAgNS44LTkuMkwyNDQuMSAxM2EyNzQuOCAyNzQuOCAwIDAgMC03NC44IDMyLjRsLTEwLjgtNWEzNzcuMyAzNzcuMyAwIDAgMSA1LjQtMy40IDY4LjIgNjguMiAwIDAgMC0zNC4zIDEuOEMxMDIgNDYuMSA4NS40IDU4IDc0LjQgNzguN2wuNyAxLjIgNS41IDEwLjUgMTkuNiAzN2E1MC40IDUwLjQgMCAwIDAgMTkgLjJjOS42LTEuNCAxOC40LTUgMjUuNS0xMC43IDE0LjEtMTEuNCAyMS42LTIwIDIyLjItMjcuNi43LTktNS4yLTIxLjEtMjEuNy00NC4xIDIzLjMgMTUuNiAzOS4yIDQwLjYgMjYuNCA1OC42di4xYTU3IDU3IDAgMCAxLTQuMyA1LjZjLTQuMiA0LjgtOS4zIDkuNS0xNi4zIDE1LjJhNjMuNCA2My40IDAgMCAxLTMwLjMgMTIuOCA2NiA2NiAwIDAgMS0xOS4xLjNsLTE4LjUgMjlhMjgwNzQuNyAyODA3NC43IDAgMCAxIDQ5LjUgMjcuNnYtLjJjNTEtMi43IDg0LTMzLjYgMTE1LjktODQuMy0yNC40IDUxLjgtNTQuNiA4NS0xMDEuMiA5Mi44IDkuOCA1LjQgMTguNiAxMC40IDI2LjYgMTUgNTAtMy4zIDgwLjItMzAuNyAxMTEuOC04MC45LTI0LjEgNTEuMi01MS45IDgxLjQtOTcgODkuMmE1NTAuNyA1NTAuNyAwIDAgMCAxNC43IDggNzUgNzUgMCAwIDEtLjUtLjUgMjIyLjMgMjIyLjMgMCAwIDAgNS41IDMgNDEwIDQxMCAwIDAgMCA4LjMgNGM0OS44LTMuMiA3Ny42LTI3LjEgMTA5LjItNzcuMy0yMy4yIDQ5LjMtNDggNzYuNS04OS43IDg1IDMwLjUgOSA1NS4yIDMuNSA4MC0xMiA4LjUtNS41IDI4LjktMzQuNSA2MS04Ny4yTDI1My42IDE2LjQgMjAxIDExMC4yYTE3Mi45IDE3Mi45IDAgMCAxLTMwLjEgMzguNCA5NCA5NCAwIDAgMS02Mi40IDIxLjV6JyBmaWxsPScjM0MwMDAwJy8+PC9zdmc+&style=flat-square)](https://github.com/evilmartians/lefthook)
[![Taskfile](https://img.shields.io/badge/Taskfile-29BEB0?logo=task&logoColor=white&style=flat-square)](https://taskfile.dev/)
[![VSCode](https://img.shields.io/badge/VSCode-0078D4?style=flat-square&logo=visual%20studio%20code&logoColor=white)](https://code.visualstudio.com/)
[![Zed](https://img.shields.io/badge/Zed-white?style=flat-square&logo=zedindustries&logoColor=084CCF)](https://zed.dev/)

A port of the StandardJS ESLint configuration to Biome.

## Installation / Getting Started

Run the following command to install the Biome configuration:

```bash
npm install git+ssh://git@github.com:robinwalterfit/biome-standard.git#v0.4.0
```

Then add to your Biome configuration:

```jsonc
{
    "$schema": "https://biomejs.dev/schemas/2.3.10/schema.json",
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
`biome migrate` will end up in merging the existing biome configuration with
the new rules. The next section will tell you what StandardJS configuration was
used to generate this Biome configuration.

### Dependencies

Run

```bash
npm install --save-dev eslint-config-love@84.1.1 eslint-config-standard@17.1.0 eslint-config-standard-jsx@11.0.0 eslint-config-standard-react@13.0.0
```

and find the packages in `node_modules`. Copy the ESLint configuration to the
root directory, name it `.eslintrc.json` and run `biome migrate` one by one.

**NOTE**: `eslint-config-love` won't export a typical `.eslintrc` configuration
file. Instead you will find a `index.js`. Copy this file and name it `.eslintrc.cjs`.

## Contributing

Read the [contributing guide](./CONTRIBUTING.md) to learn about our
development process, how to propose bug fixes and improvements, and how to build
and test your changes.

## Versioning

[SemVer](https://semver.org/) is used for versioning. For the versions
available, see the tags on this repository.

To make versioning as easy as possible, this project uses
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) along
with the tool [Cocogitto](https://docs.cocogitto.io/). This way it is very
easy to calculate a new version number and generate changelogs based on commit
messages.

## Links

- Biome configuration based on Standard: [https://github.com/robinwalterfit/biome-standard](https://github.com/robinwalterfit/biome-standard)
- Issue tracker: [https://github.com/robinwalterfit/biome-standard/issues](https://github.com/robinwalterfit/biome-standard/issues)
- More Links:
    - Biome: [https://biomejs.dev/](https://biomejs.dev/)
    - Biome repository: [https://github.com/biomejs/biome](https://github.com/biomejs/biome)
    - Cocogitto: [https://docs.cocogitto.io/](https://docs.cocogitto.io/)
    - Collection of useful `.gitattributes` templates: [https://github.com/gitattributes/gitattributes](https://github.com/gitattributes/gitattributes)
    - Contributor Covenant Code of Conduct: [https://www.contributor-covenant.org/version/2/1/code_of_conduct.html](https://www.contributor-covenant.org/version/2/1/code_of_conduct.html)
    - Conventional Branch: [https://conventional-branch.github.io/](https://conventional-branch.github.io/)
    - Conventional Commits: [https://www.conventionalcommits.org/en/v1.0.0/](https://www.conventionalcommits.org/en/v1.0.0/)
    - EditorConfig: [https://editorconfig.org/](https://editorconfig.org/)
    - Git Flow: [https://nvie.com/posts/a-successful-git-branching-model/](https://nvie.com/posts/a-successful-git-branching-model/)
    - `.gitignore` Generator: [https://gitignore.io](https://gitignore.io)
    - keep a changelog: [https://keepachangelog.com/en/1.1.0/](https://keepachangelog.com/en/1.1.0/)
    - Lefthook: [https://github.com/evilmartians/lefthook](https://github.com/evilmartians/lefthook)
    - Semantic Versioning: [https://semver.org/](https://semver.org/)
    - StandardJS: [https://standardjs.com/](https://standardjs.com/)
        - `eslint-config-love@84.1.1`: [https://github.com/mightyiam/eslint-config-love/tree/v84.1.1](https://github.com/mightyiam/eslint-config-love/tree/v84.1.1)
        - `eslint-config-standard@17.1.0`: [https://github.com/standard/eslint-config-standard/tree/v17.1.0](https://github.com/standard/eslint-config-standard/tree/v17.1.0)
        - `eslint-config-standard-jsx@11.0.0`: [https://github.com/standard/eslint-config-standard-jsx/tree/v11.0.0](https://github.com/standard/eslint-config-standard-jsx/tree/v11.0.0)
        - `eslint-config-standard-react@13.0.0`: [https://github.com/standard/eslint-config-standard-react/tree/v13.0.0](https://github.com/standard/eslint-config-standard-react/tree/v13.0.0)
    - Taskfile: [https://taskfile.dev/](https://taskfile.dev/)
    - Visual Studio Code: [https://code.visualstudio.com/](https://code.visualstudio.com/)
    - Zed: [https://zed.dev/](https://zed.dev/)

## License

`biome-standard` is [MIT licensed](./LICENSE-MIT) or [Apache 2.0 licensed](./LICENSE-APACHE) and moderated under the [Contributor Covenant Code of Conduct](./.github/CODE_OF_CONDUCT.md).
