# tsconfig

Shared [TypeScript TSConfig Base](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects.

[![NPM version][npm-badge]][npm-url]
[![License][license-badge]][license-url]

## Install

```sh
npm install @epreston/tsconfig --save-dev
```

## Usage

`tsconfig.json`

```json
{
  "extends": "@epreston/tsconfig",
  "compilerOptions": {
    "outDir": "temp"
  }
}
```

## Tools

| Tool         | Reference                       |
| ------------ | ------------------------------- |
| TypeScript   | https://www.typescriptlang.org/ |
| Node.js      | https://nodejs.org/             |
| EditorConfig | https://editorconfig.org        |

## References

| Website  | Reference               |
| -------- | ----------------------- |
| TSConfig | https://aka.ms/tsconfig |

## License

This project is released under the MIT [License](LICENSE).

[npm-badge]: https://img.shields.io/npm/v/@epreston/tsconfig
[npm-url]: https://www.npmjs.com/package/@epreston/tsconfig
[license-badge]: https://img.shields.io/npm/l/@epreston/tsconfig.svg
[license-url]: LICENSE
