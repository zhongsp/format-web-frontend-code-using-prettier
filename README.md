[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

# Format web front-end code using Prettier

> By utilizing a tool, the whole team could have a consistent code formatting style.

Prettier is an opinionated code formatter with support for:

- JavaScript, including ES2017
- JSX
- Flow
- TypeScript
- CSS, Less, and SCSS
- JSON
- GraphQL
- Markdown, including GFM
- YAML

## Install into Visual Studio Code

Download `Visual Studio Code` and install this extension.

- Open `Extensions`
- Search `Prettier - Code formatter` with publisher name `Esben Petersen`
- Click `Install`

## Format code

- Right click code area and select `Format Document`, or
- Use shortcut `Ctrl + Alt + F` on Windows, or
- Enable `format on save`, or
- etc.

## Format settings

Settings will be read from (listed by priority):

- A Prettier configuration file, e.g: [.prettierrc](./.prettierrc)
- An EditorConfig file, e.g.: [.editorconfig](./.editorconfig)

We should use a `.editorconfig` file together, as modern editors like Visual Studio Code could make use of it.
