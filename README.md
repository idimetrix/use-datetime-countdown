# use-datetime-countdown
A customizable countdown hook for React

## Installation

To install the package, use npm:

```bash
pnpm add use-datetime-countdown

yarn install use-datetime-countdown

npm install use-datetime-countdown
```

## Usage

```typescript
import { useDatetimeCountdown } from 'use-datetime-countdown';

const date = new Date('2025-01-01T01:00:00.001Z');

const datetime = useDatetimeCountdown();

console.log(datetime);

// {
//     days: ...,
//     hours: ...,
//     minutes: ...,
//     seconds: ...,
// }
```

## tsup
Bundle your TypeScript library with no config, powered by esbuild.

https://tsup.egoist.dev/

## How to use this
1. install dependencies
```
# pnpm
$ pnpm install

# yarn
$ yarn install

# npm
$ npm install
```
2. Add your code to `src`
3. Add export statement to `src/index.ts`
4. Test build command to build `src`.
Once the command works properly, you will see `dist` folder.

```zsh
# pnpm
$ pnpm run build

# yarn
$ yarn run build

# npm
$ npm run build
```
5. Publish your package

```zsh
$ npm publish
```


## test package
https://www.npmjs.com/package/use-datetime-countdown
