# tsconfig

> Official [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) used by osskit

## Install

```sh
yarn add --dev @osskit/tsconfig
```

*This config requires TypeScript 4.7 or later.*

## Usage

`tsconfig.json`

```json
{
	"extends": "@osskit/tsconfig",
	"compilerOptions": {
      "outDir": "dist"
	},
    "include": ["src/**/*"]
}
```

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
	"extends": "@osskit/tsconfig",
	"compilerOptions": {
      "outDir": "dist",
      "target": "ES2021"
	},
    "include": ["src/**/*"]
}
```
